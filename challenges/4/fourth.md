
# Task 4: Speech-to-Text (ASR Model using Librispeech)

**Goal:** Train an Automatic Speech Recognition (ASR) model using RNNs or Transformers.

**Steps:**
1. **Data Loading & Feature Extraction**
   - Use `torchaudio.datasets.LIBRISPEECH`
   - Convert audio waveforms to spectrograms (Mel-Spectrogram)
2. **Build Model**
   - Use an RNN (LSTM/GRU) or Transformer
   - Add CTC loss for alignment-free decoding
3. **Define Loss & Optimizer**
   - Use CTCLoss for sequence-to-sequence learning
   - Adam optimizer
4. **Training**
   - Implement batch processing with DataLoader
   - Train with backpropagation & gradient clipping
5. **Testing & Evaluation**
   - Compute WER (Word Error Rate)
   - Test on unseen speech samples
