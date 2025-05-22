# Hate Speech Recognition using Machine Learning

This project implements a machine learning-based approach to classify tweets into Hate Speech, Offensive Language, or Neither. It uses traditional ML classifiers and evaluates their performance on a real-world labeled dataset, with detailed preprocessing and analysis.

## 📌 Features
Preprocessing of raw tweets (removing mentions, links, hashtags, punctuation, etc.)

Feature extraction using TF-IDF vectorization

Multiclass classification using:

Logistic Regression

Multinomial Naive Bayes

Random Forest

Model evaluation using:

Accuracy, Precision, Recall, F1-Score

Confusion Matrix (visualized with Seaborn)

## 🗂️ Dataset
Source: labeled_data.csv (originally from Davidson et al.)

Classes:

0: Hate Speech

1: Offensive Language

2: Neither

## 📈 Performance Overview
Model	Accuracy	Notable Observations
Logistic Regression	~89%	Strong balance, but lower performance for class 0
Naive Bayes	~80%	Performs well for class 1, but poorly on others
Random Forest	~89%	Better macro-average, improved class 2 detection
