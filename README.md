# 📩 SMS Spam Detection using Natural Language Processing (NLP)

## Overview

This project is a machine learning-based SMS Spam Detection system that classifies text messages as either **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

The objective of this project was to build a complete text classification pipeline—from preprocessing raw text data to training and evaluating multiple machine learning models.

---

## Dataset

The project uses the **SMS Spam Collection Dataset**, which contains thousands of labeled SMS messages categorized as:

- Spam
- Ham (Legitimate messages)

---

## Project Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Model Evaluation
7. Model Serialization using Pickle

---

## Text Preprocessing

The following preprocessing steps were performed:

- Converted text to lowercase
- Tokenized text using NLTK
- Removed punctuation and special characters
- Removed English stopwords
- Applied Porter Stemming
- Generated cleaned text for feature extraction

---

## Feature Extraction

The cleaned text was converted into numerical features using:

- **TF-IDF Vectorizer**

This enables machine learning algorithms to process and learn from textual data.

---

## Machine Learning Models Evaluated

The following classification algorithms were trained and compared:

- Gaussian Naive Bayes
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Extra Trees Classifier

The final model was selected based on its evaluation metrics.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Confusion Matrix

Since spam detection is an imbalanced classification problem, **Precision** was considered an important metric while selecting the final model.

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud
- Pickle

---

## Files Included

```text
spam_detection.ipynb     # Complete notebook
spam.csv                 # Dataset
model.pkl                # Trained model
vectorizer.pkl           # TF-IDF Vectorizer
README.md
requirements.txt
```

---

## Author

**Akshat Raj**
