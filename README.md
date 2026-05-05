# Hate Speech Detection using NLP & Machine Learning

A comprehensive Natural Language Processing (NLP) project for detecting hate speech across multiple datasets using machine learning and deep learning techniques.

---

## Overview

This project focuses on building robust hate speech detection models using different datasets and approaches. It explores preprocessing techniques, feature engineering, and model comparisons to classify text into:

- Hate Speech
- Offensive Language
- Non-Hate / Neutral Content

---

## Project Structure
```
├── HateSpeechDeepa.ipynb
├── HateXplain.ipynb
├── IndoHateSpeech.ipynb
├── Kaggle_hate_nonHate.ipynb
└── README.md
```
---

## Datasets Used

### HateXplain Dataset
- Annotated dataset with rationales
- Includes explainability features

### Indo Hate Speech Dataset
- Focused on multilingual/Indian context
- Useful for regional language handling

### Kaggle Hate/Non-Hate Dataset
- Binary classification dataset
- Clean and structured

### A Dataset of Hindi-English Code-Mixed Social Media Text for Hate Speech Detection
- Relatively Noisy

---

## Features & Techniques

### Text Preprocessing
- Lowercasing
- Stopword removal
- Tokenization
- Stemming / Lemmatization
- Noise removal (URLs, punctuation, etc.)

### Feature Engineering
- TF-IDF Vectorization

### Models Used
- mBERT
- -mBERT + Class Weights
- XLM-RoBERTa
- Logistic Regression
- Support Vector Machine (SVM)

---

## Model Evaluation

- Accuracy
- F1 Score (mainly focused)
- Precision
- Recall

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/hate-speech-detection.git
cd hate-speech-detection
```
