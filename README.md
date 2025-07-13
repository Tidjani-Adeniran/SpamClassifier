# 📧 Spam Email Classifier using Multinomial Naive Bayes and TF-IDF

## 🧑‍💻 Author
Tidjani Adeniran  
Fourth-Year Computer Science Student – West End University College

---

## 📌 Project Description

This project implements a **Spam Email Classifier** using Natural Language Processing (NLP) and **Multinomial Naive Bayes (MNB)**. It is designed to automatically distinguish between **spam** (unsolicited messages) and **ham** (legitimate emails) based on the content of the email text.

The classifier is built using the **TF-IDF vectorization technique** for feature extraction and the **MNB algorithm** for classification. The goal is to create an accurate, lightweight, and efficient system that can be deployed in real-world email filtering systems.

---

## 🗂️ Dataset

- **Name**: Spambase Dataset  
- **Source**: UCI Machine Learning Repository  
- 🔗 [https://archive.ics.uci.edu/ml/datasets/spambase](https://archive.ics.uci.edu/ml/datasets/spambase)  
- **Format**: CSV (`Book1.csv` used in this project)

---

## ⚙️ Features Implemented

- Email text cleaning (lowercase, punctuation removal, HTML tag stripping, etc.)
- TF-IDF vectorization of text data
- Added email length as an additional feature
- Training/testing split (80% train / 20% test)
- Model training with **Multinomial Naive Bayes**
- Hyperparameter tuning (alpha smoothing values)
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - Confusion matrix
- Interactive user input for real-time spam prediction

---

## 🧪 Experimental Results

- **Best Alpha (α)**: 0.5  
- **Accuracy**: 98.57%  
- **Precision (Spam)**: 1.000  
- **Recall (Spam)**: 0.90  
- The classifier performs exceptionally well in avoiding false positives, with some room for improving recall.

---

## 📈 Next Steps

- Add more engineered features (spam trigger words, excessive punctuation, etc.)
- Perform advanced hyperparameter tuning using `GridSearchCV`
- Handle class imbalance via oversampling or undersampling
- Experiment with alternative models (Logistic Regression, SVM)
- Conduct error analysis on false negatives

---

## 📦 Installation & Usage

### Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib (optional, for visualizations)

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-email-classifier.git
   cd spam-email-classifier
