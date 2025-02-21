# Task 2: Sentiment Analysis (IMDB Movie Reviews)

**Goal:** Train an LSTM model to classify IMDB reviews as positive or negative.

**Steps:**
1. **Data Loading & Tokenization**
   - Use `torchtext.datasets.IMDB`
   - Convert text to numerical sequences (word embeddings)
2. **Build Model**
   - Use an Embedding layer (e.g., pre-trained GloVe)
   - LSTM with dropout & fully connected layers
3. **Define Loss & Optimizer**
   - Binary CrossEntropyLoss, Adam optimizer
4. **Training**
   - Use PyTorch Dataset & DataLoader
   - Train using backpropagation
5. **Testing & Evaluation**
   - Use accuracy, F1-score, ROC curve
   - Test on unseen movie reviews
