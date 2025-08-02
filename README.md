# Twitter Sentiment Analysis Project 🐦📊

## Overview
This project performs **sentiment analysis** on a large dataset of Twitter messages (1.6 million tweets) to classify messages as positive or negative. The goal is to build a robust natural language processing (NLP) pipeline that cleans raw tweet data, extracts features, trains a classification model, and evaluates its performance.

---

## 📊 Dataset

The dataset consists of **1.6 million pre-labeled Twitter messages** intended for sentiment analysis.

### 📌 Features per Tweet

- **Sentiment Label**:  
  - `0` = Negative sentiment  
  - `1` = Positive sentiment  
- **Tweet ID**: Unique identifier for the tweet  
- **Timestamp**: Date and time when the tweet was posted  
- **Query**: The search term used (mostly `"NO_QUERY"`)  
- **Username**: Twitter handle of the user who posted the tweet  
- **Text**: Full tweet content

### 📁 Source

- [Sentiment140 Twitter Dataset on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Originally compiled in 2009
---

## Key Objectives
- Preprocess raw tweets by removing noise (URLs, mentions, special characters).
- Remove stopwords and perform stemming on tweet text.
- Convert cleaned text into numerical features using TF-IDF vectorization.
- Train a logistic regression classifier to predict sentiment labels.
- Evaluate model accuracy and interpret key results.

---

## Technologies Used
- **Python** (Pandas, NumPy) for data ingestion and manipulation
- **NLTK** for text preprocessing (stopwords removal, stemming)
- **scikit-learn** for machine learning (TF-IDF vectorization, logistic regression)
- **Jupyter Notebook** for exploratory data analysis and prototyping

---


## Future Enhancements
- Experiment with advanced models (e.g., LSTM, BERT).
- Implement cross-validation and hyperparameter tuning.
- Add sentiment visualization dashboards.
- Expand to multi-class sentiment classification.

---

> _This project showcases applied NLP, data preprocessing, and machine learning on social media data—key skills for data science and AI roles._

