# 🐦 Twitter Sentiment Analysis using Machine Learning

A machine learning project to classify tweets as **positive** or **negative** using natural language processing and logistic regression. Built in **Python** and developed using **Google Colab** with the **Sentiment140** dataset.

---

## 📌 Overview

This project demonstrates the complete ML pipeline:

- Data collection from Kaggle (1.6M tweets)
- Text preprocessing (cleaning, stop word removal, stemming)
- Feature extraction using **TF-IDF**
- Model training using **Logistic Regression**
- Evaluation on unseen data
- Model saving and reuse for predictions

---

## 📊 Dataset

- **Name**: Sentiment140  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)  
- **Size**: ~1.6 million tweets  
- **Labels**:
  - `0` → Negative
  - `4` → Positive (converted to `1` for binary classification)

---

## 🔧 Technologies & Libraries

- Python
- Pandas, NumPy
- NLTK (text preprocessing)
- Scikit-learn (Logistic Regression, TF-IDF, train-test split)
- Pickle (model saving)
- Google Colab

---

## 🔁 Workflow

1. **📥 Data Collection**
   - Loaded via Kaggle API inside Google Colab

2. **🧼 Preprocessing**
   - Remove non-alphabetic characters, URLs, mentions
   - Lowercasing, tokenization, stopword removal, stemming (PorterStemmer)

3. **🧠 Feature Engineering**
   - TF-IDF vectorization of cleaned tweets

4. **📈 Model Training**
   - Logistic Regression trained with 80% of the data
   - Accuracy:
     - **Train**: ~79%
     - **Test**: ~77%

6. **📤 Prediction**
   - Predicts as **Positive** or **Negative**

---
