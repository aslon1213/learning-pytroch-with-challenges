

# Task 1: Image Classification (CIFAR-10)

Goal: Build a CNN model to classify CIFAR-10 dataset images.

Steps:

1. Data Loading & Preprocessing
   - Use `torchvision.datasets.CIFAR10`
   - Normalize & augment images (e.g., random crop, flip)
2. Build Model
   - CNN with `Conv2d`, `ReLU`, `MaxPool2d`, `Linear`
   - Use `BatchNorm2d` & `Dropout`
3. Define Loss & Optimizer
   - `CrossEntropyLoss`, `Adam`/`SGD` optimizer
4. Training
   - Use mini-batch gradient descent
   - Implement training loop with backpropagation
5. Testing & Evaluation
   - Calculate accuracy, precision, recall
   - Plot loss & accuracy curves
