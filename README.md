# Credit-Card-Fraud-Detection

A machine learning project that detects fraudulent credit card transactions using anomaly detection and supervised classification methods. Built using Python and scikit-learn on an imbalanced dataset.

---

##  Project Overview

This project focuses on identifying fraudulent credit card transactions using machine learning. It involves preprocessing, handling imbalanced data, and applying classification models to distinguish between legitimate and fraudulent transactions.

---

##  Features

- Data cleaning and preprocessing
- Handling class imbalance using:
  - **Under-sampling**
  - **Over-sampling (SMOTE)**
- Feature scaling
- Trained with models like:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Model evaluation using:
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC-AUC Curve

---

##  Technologies Used

- **Python**
- **scikit-learn**
- **pandas & numpy**
- **matplotlib & seaborn** – visualization
- **imbalanced-learn** – SMOTE

---

##  Dataset

- [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains anonymized transaction data (284,807 rows) with a severe class imbalance.

---

## Getting Started

###  Prerequisites

Install required packages:

```bash
pip install -r requirements.txt
