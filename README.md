# Credit Card Fraud Detection Using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced and requires special handling to effectively identify fraudulent behavior while minimizing false positives.

---

## 📊 Dataset

* **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)
* **Details**:

  * Contains 284,807 transactions, including 492 fraud cases.
  * Features: 30 total — `Time`, `Amount`, anonymized variables `V1` to `V28`, and `Class` (0 = Normal, 1 = Fraud).
  * Highly imbalanced (\~0.17% fraud rate).

---

## 🔍 Objectives

* Explore and preprocess the dataset
* Train and evaluate multiple classification models
* Compare performance metrics to identify the most effective approach

---

## 🧠 Models Used

*  k-nearest Neighbors (KNN)
* Logistic Regression
* Support Vector Machines (SVM)
* Naive Bayes.

---

## 📈 Evaluation Metrics

Given the dataset's imbalance, the following metrics were prioritized:

* **Precision**
* **Recall**
* **F1-Score**

---

## ⚙️ Requirements

* Python 3.x
* pandas, numpy, matplotlib, seaborn
* scikit-learn
