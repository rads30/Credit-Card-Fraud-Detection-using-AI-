# Credit-Card-Fraud-Detection-using-AI-
Detecting credit card fraud using Isolation Forest and the Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
# AI-Powered Fraud Detection 🚨💳

Detecting credit card fraud using Isolation Forest and the Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

Input Data Description:
The input dataset used for fraud detection is the Credit Card Fraud Detection Dataset provided on Kaggle. Here are the important details of the data:

Dataset Name: Credit Card Fraud Detection

Link: Kaggle Dataset

Data Columns:

V1 to V28: PCA-transformed features representing various characteristics of the transaction.

Time: Time elapsed between this transaction and the first transaction in the dataset (not needed for anomaly detection).

Amount: The amount of money involved in the transaction.

Class: Label for fraud detection. 1 indicates fraud, and 0 indicates a legitimate transaction.


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
