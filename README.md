# **Toxic Comment Classification**

# Overview

This project explores the efficacy of various machine learning models for toxic comment classification, comparing traditional algorithms with state-of-the-art transformer-based models and an attention-based BiLSTM-CNN architecture. The goal is to identify the most effective model for detecting and categorizing online toxicity into multiple classes.

# Features

Multi-Class Classification: Classifies comments into categories such as toxic, severe toxic, obscene, threat, insult, and identity hate.

Model Comparisons: Evaluates traditional models alongside advanced transformer-based models

**Traditional Models**:
Logistic Regression
Linear SVC
Multinomial Naive Bayes

**Advanced Models**:
BERT
RoBERTa
DistilBERT

Performance Metrics: Accuracy, precision, recall, and F1-score.

Preprocessing: Implements text cleaning, tokenization, and TF-IDF vectorization.

Our Approach Utilizes **attention layers in the BiLSTM-CNN** to focus on critical parts of the input text.

# Results

The Attention-Based BiLSTM-CNN model achieved the highest accuracy of 98.6%, outperforming both traditional and transformer-based models across all metrics.
