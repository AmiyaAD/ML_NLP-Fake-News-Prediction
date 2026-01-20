# 📰 Fake News Prediction

## 📌 Overview
Fake news has become a major challenge in today’s digital world, spreading misinformation across social media and online platforms.  
This project aims to **detect and classify news articles as real or fake** using **Machine Learning (ML) and Natural Language Processing (NLP)** techniques.

---

## 🚀 Features
- Preprocessing of text data (tokenization, stopword removal, stemming/lemmatization).
- Feature engineering with TF-IDF, Bag-of-Words, and custom n-grams.
- Multiple ML models tested: Logistic Regression, Random Forest, Dicison Tree, SVR, KNN.
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.


---

📊 Dataset
- Commonly used dataset: Fake News Dataset from Kaggle (kaggle.com in Bing)
- Contains labeled news articles with title, text, subject, and label.

📈 Results
- Logistic Regression baseline: 


Classical Model details here :                precision    recall  f1-score   support

           0       0.99      1.00      1.00       365
           1       1.00      0.99      1.00       381

    accuracy                           1.00       746
   macro avg       1.00      1.00      1.00       746
weighted avg       1.00      1.00      1.00       746
