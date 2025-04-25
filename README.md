# Credit-Card-Fraud-Detection-using-AI-
Detecting credit card fraud using Isolation Forest and the Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
# AI-Powered Fraud Detection 🚨💳

Detecting credit card fraud using Isolation Forest and the Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## 📁 Dataset
- 284,807 transactions
- 492 frauds (Class = 1)

## 📊 Features
- `V1` to `V28` (PCA components)
- `Amount` (transaction amount)
- `Class` (fraud label)

## 🧠 Model
- Unsupervised Isolation Forest
- Handles class imbalance without needing labels for training

## 📈 Results
- Evaluated using confusion matrix and classification report
- Anomaly scores visualized for threshold tuning


## 📎 Output
- `fraud_cases_detected.csv`: Export of suspected fraud transactions
