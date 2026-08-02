# Twitter Sentiment Analysis using Machine Learning

A Machine Learning project that classifies Twitter posts into different sentiment categories using Natural Language Processing (NLP) techniques.

---

## Project Overview

This project performs **Twitter Sentiment Analysis** by preprocessing tweet text, extracting meaningful features using NLP, and training a Machine Learning model to predict the sentiment of unseen tweets.

The notebook includes the complete workflow from data loading to model training, evaluation, and model saving.

---

## Features

- Exploratory Data Analysis (EDA)
- Text preprocessing
- Tokenization
- Stopword removal
- Stemming & Lemmatization
- TF-IDF Vectorization
- Random Forest Classifier
- Model Evaluation
- Save trained model using Pickle

---

## Dataset

The dataset contains four columns:

| Column | Description |
|---------|-------------|
| Tweet_ID | Unique Tweet ID |
| Entity | Company/Product mentioned |
| Sentiment | Target label |
| Tweet | Tweet text |

Example sentiments include:

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

```
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

## Project Structure

```
Twitter-Sentiment-Analysis/
│
├── Twitter-sentiment.ipynb
├── twitter_training.csv
├── model.pkl
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/twitter-sentiment-analysis.git
```

Move into the project:

```bash
cd twitter-sentiment-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

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

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
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
- Streamlit Web App
- Flask REST API
- Hyperparameter Tuning

---
