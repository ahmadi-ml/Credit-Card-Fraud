# Credit Card Fraud Detection using Random Forest

This repository contains a Machine Learning project focused on detecting fraudulent credit card transactions. Given the highly imbalanced nature of fraud datasets, this project implements a **Random Forest Classifier** and evaluates its performance using robust classification metrics.

---

## 📌 Project Overview
Anatomic monitoring of credit card transactions is essential for financial institutions to prevent fraud. The primary challenge of this task is that fraudulent transactions are extremely rare compared to legitimate ones. This project addresses this challenge by utilizing ensemble learning techniques to achieve high precision and recall.

---

## 📊 Dataset
The dataset used in this project is typically the **Credit Card Fraud Detection** dataset (available on Kaggle).
* **Total Transactions:** 284,807 (simulated or real standard Kaggle format)
* **Classes:** Legitimate (0) vs. Fraudulent (1)
* **Data Nature:** Highly imbalanced (Fraud cases usually make up less than 0.2% of the dataset).

---

## 🛠️ Technologies & Libraries Used

This project was developed using **Python 3.x** and the following major libraries:

* **Scikit-Learn:** For data splitting (`train_test_split`), training the `RandomForestClassifier`, and evaluating models.
* **Pandas & NumPy:** For data cleaning, manipulation, and matrix operations.
* **Matplotlib & Seaborn:** For exploratory data analysis (EDA) and plotting the Confusion Matrix.

---

## 📈 Results & Evaluation

Since accuracy is misleading for imbalanced datasets, the model was evaluated using **Precision, Recall, and the Confusion Matrix**:

###  Classification Report
```text
[متن خروجی classification_report 

              precision    recall  f1-score   support
           0       1.00      1.00      1.00     85285
           1       0.98      0.80      0.88       158


       