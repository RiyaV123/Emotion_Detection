This project implements an emotion classification model using Bidirectional LSTM (BiLSTM) to detect human emotions (e.g., happy, sad, angry) from raw text data. It includes data preprocessing, class balancing, model training, and saving components for deployment.

Features:
Text preprocessing (cleaning, tokenization, padding)
Bidirectional LSTM model for multi-class emotion detection
Handled class imbalance using RandomOverSampler
Performance visualization and test evaluation
Model, tokenizer, and label encoder saved for deployment

 Model Architecture
Embedding Layer → BiLSTM (128) → BatchNorm + Dropout
→ BiLSTM (64) → BatchNorm + Dropout
→ Dense (32, ReLU) → BatchNorm → Dense (Softmax)

Dataset
A labeled dataset of text-emotion pairs (e.g., tweets with emotion tags).
Each entry has a text and a corresponding label.
You can replace the dataset with any CSV having text and label columns.

Results
Achieved 97% test accuracy (update with actual result).



