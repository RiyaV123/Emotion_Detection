Emotion Detection 
This project uses deep learning and natural language processing (NLP) to detect emotions in text. Built with Python and Streamlit, it provides a simple web interface where users can input a sentence and get the predicted emotion in real-time.


FEATURES:
-  Detects emotions like *happy*, *sad*, *angry*, etc.
-  Uses a pre-trained deep learning model for classification
-  Interactive UI built with Streamlit
-  Includes data preprocessing and visualization
-  Trained and tested on a labeled dataset

Tech Stack
- Python
- TensorFlow / Keras
- Streamlit
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn

Model used: 
A CNN-based text classifier built with Keras. It includes:
Embedding for word vectors
Conv1D + GlobalMaxPooling for feature extraction
Dense layers for emotion classification (6 classes)
Trained on a labeled emotion dataset.
