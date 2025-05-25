# EEG Emotion Classification using Machine Learning

This project classifies human emotional states using EEG signal features extracted from biosignals. We explore multiple machine learning models to predict emotion categories based on brainwave activity.


##  Dataset
- **Source:** [Kaggle - EEG Brainwave Dataset: Feeling Emotions](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions)
- Contains statistical and frequency-domain features derived from raw EEG signals
- Target labels: `POSITIVE`, `NEGATIVE`, `NEUTRAL`


##  Methods
- Label Encoding
- Feature Normalization using `StandardScaler`
- Machine Learning Models:
  -  Random Forest (99.0% Accuracy)
  - Logistic Regression (97.4%)
  - SVM (95.8%)


##  Results
Random Forest achieved the highest accuracy with great generalization on validation data.


##  How to Run This Project

1. Clone the repository  
2. Install dependencies from `requirements.txt`:

pip install -r requirements.txt
