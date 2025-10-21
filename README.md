# Hate-Speech-Classifier-System
A machine learning–based hate speech classification system trained on over 48,000 Kenyan tweets from the 2017 presidential elections.
Tweets are categorized as Hate Speech, Offensive, or Neither, using NLP and supervised learning techniques.

## Overview
This project demonstrates how Natural Language Processing (NLP) and Machine Learning (ML) can be applied to automatically detect hate speech in social media data.
The system analyzes tweets, extracts linguistic features, and classifies them into one of three categories to support responsible online communication.

### Dataset
Total Records: 48,057 tweets
Source: Kenyan presidential elections (Aug & Oct 2017)
Labels:
0: Neither
1: Offensive
2: Hate Speech

Annotation: Each tweet was labeled by at least 3 annotators; the majority vote determined the final label.

## Project workflow
Data Preprocessing
Cleaning text (mentions, URLs, hashtags, punctuation)
Tokenization, stopword removal, and lemmatization
Handling class imbalance via sampling or class weighting

Feature Engineering
TF-IDF vectorization
Optional word embeddings (Word2Vec or GloVe)

Model Training
Algorithms used:
Logistic Regression
Random Forest
XGBoost
LSTM (optional deep learning variant)
Hyperparameter tuning with GridSearchCV

Model Evaluation
Metrics: Accuracy, Precision, Recall, F1-Score, AUC
Visualization: Confusion Matrix, ROC Curves
Cross-validation to ensure robustness

### Model Insights
Language: English & Swahili mix
Task: Multiclass text classification
Libraries Used: scikit-learn, xgboost, pandas, numpy, nltk, matplotlib
Explainability: SHAP used for feature importance visualization

## Ethical Considerations
Built for academic and research purposes only
Not intended for automated censorship or content moderation
Data anonymized and used under fair research use
Human oversight is essential when interpreting results
