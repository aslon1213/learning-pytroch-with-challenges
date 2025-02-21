
# Task 3: Object Detection (YOLO-Like Model on COCO)

**Goal:** Train a CNN-based object detector for COCO dataset.

**Steps:**
1. **Data Loading & Augmentation**
   - Load COCO dataset using `torchvision.datasets.CocoDetection`
   - Resize, normalize images
2. **Build Model**
   - Use ResNet as backbone
   - Add feature pyramid network (FPN) & bounding box regression head
3. **Define Loss & Optimizer**
   - Use `torchvision.ops.FocalLoss` for classification
   - Smooth L1 Loss for bounding box regression
4. **Training**
   - Use multi-scale augmentation & batch gradient descent
   - Implement anchor box generation
5. **Testing & Evaluation**
   - Compute IoU (Intersection over Union)
   - Draw bounding boxes on test images
