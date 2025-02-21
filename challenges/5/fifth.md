
# Task 5: Anomaly Detection (Autoencoder on Time-Series Data)

**Goal:** Train an Autoencoder to detect anomalies in time-series data.

**Steps:**
1. **Data Loading & Preprocessing**
   - Use a time-series dataset (e.g., NASA Bearing Dataset)
   - Normalize & create sliding window sequences
2. **Build Model**
   - Create an Autoencoder (Encoder + Decoder)
   - Use LSTM or Transformer-based architecture
3. **Define Loss & Optimizer**
   - Use MSELoss for reconstruction error
   - Adam optimizer
4. **Training**
   - Minimize reconstruction loss
   - Use early stopping to avoid overfitting
5. **Testing & Evaluation**
   - Compute anomaly score (MSE between input & reconstructed output)
   - Detect anomalies based on a threshold
