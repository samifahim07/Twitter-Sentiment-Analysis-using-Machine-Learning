# Twitter Sentiment Analysis using NLP

A Machine Learning project that classifies Twitter posts into different sentiment categories using Natural Language Processing (NLP) techniques.

---

## Project Overview

This project performs **Twitter Sentiment Analysis** by preprocessing tweet text, extracting meaningful features using NLP, and training a Machine Learning model to predict the sentiment of unseen tweets.

The notebook includes the complete workflow from data loading to model training, evaluation, and model saving.

---

## Features

- Exploratory Data Analysis (EDA)
- Text Preprocessing
- Tokenization
- Stopword Removal
- Stemming & Lemmatization
- TF-IDF Vectorization
- Random Forest Classifier
- Model Evaluation
- Save Trained Model using Pickle

---

## Dataset

The dataset contains four columns:

| Column | Description |
|---------|-------------|
| Tweet_ID | Unique Tweet ID |
| Entity | Company/Product Mentioned |
| Sentiment | Target Label |
| Tweet | Tweet Text |

### Sentiment Classes

- Positive
- Negative
- Neutral
- Irrelevant

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Pickle

---

## Machine Learning Pipeline

```text
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Text Preprocessing
      │
      ▼
Tokenization
      │
      ▼
Stopword Removal
      │
      ▼
Stemming & Lemmatization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train-Test Split
      │
      ▼
Random Forest Classifier
      │
      ▼
Model Evaluation
      │
      ▼
Save Model (.pkl)
```

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
pickle
```

---

## NLP Techniques Used

- Lowercasing
- Removing URLs
- Removing Special Characters
- Removing Punctuation
- Removing Numbers
- Removing Stopwords
- Tokenization
- Stemming
- Lemmatization
- TF-IDF Feature Extraction

---

## Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Deep Learning (LSTM)
- BERT / RoBERTa
- Streamlit Web Application
- Flask REST API
- Hyperparameter Tuning

---
