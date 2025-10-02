# Sibling Languages Classifier

Binary classification system for distinguishing between two related languages using machine learning.

## 📋 Overview

This project implements a machine learning pipeline for binary text classification of two closely related languages. The classifier uses traditional ML approaches (Logistic Regression with TF-IDF/Count features) to distinguish between similar linguistic patterns.

## 🛠️ Tech Stack

- **Data Processing**: pandas, numpy, datasets (HuggingFace)
- **ML Framework**: scikit-learn
  - Feature Extraction: TfidfVectorizer, CountVectorizer
  - Model: Logistic Regression
- **Evaluation**: classification metrics, confusion matrix
- **Visualization**: matplotlib, seaborn

## 🚀 Features

- Binary classification of related languages
- TF-IDF and Count-based feature extraction
- Performance metrics and visualization
- Confusion matrix analysis
- Model evaluation and comparison

## 📊 Pipeline

1. **Data Loading**: Load dataset using HuggingFace datasets
2. **Preprocessing**: Text cleaning and preparation
3. **Feature Engineering**: TF-IDF/Count vectorization
4. **Model Training**: Logistic Regression classifier
5. **Evaluation**: Accuracy, F1-score, confusion matrix
6. **Visualization**: Performance metrics plots

## 📈 Metrics

The model is evaluated using:
- Accuracy Score
- F1 Score
- Classification Report
- Confusion Matrix

## 🔧 Installation
```bash
pip install datasets pandas numpy scikit-learn matplotlib seaborn
```