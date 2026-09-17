# Credit Card Fraud Detection

## Overview

This project focuses on detecting fraudulent credit card transactions using
machine learning techniques.

The project uses the IEEE-CIS Fraud Detection dataset and applies data
preprocessing, SMOTE for handling class imbalance, and machine learning
models for fraud classification.

## Objective

To build a machine learning model that can identify fraudulent transactions
and evaluate its performance using appropriate classification metrics.

## Dataset

IEEE-CIS Fraud Detection Dataset.

The dataset contains transaction-related information and the target variable
`isFraud`, which indicates whether a transaction is fraudulent.

## Methodology

1. Data loading and preprocessing
2. Handling missing values
3. Selection of numerical features
4. Train-test split
5. Feature scaling
6. Handling class imbalance using SMOTE
7. XGBoost model training
8. Threshold tuning
9. Model evaluation
10. SVM baseline comparison
11. Feature importance analysis
12. Final fraud prediction generation

## Models

- XGBoost Classifier
- Support Vector Machine (SVM) with RBF kernel

## Evaluation Metrics

- Precision
- Recall
- F1 Score
- ROC-AUC
- Classification Report

## Project Structure

```text
credit-card-fraud-detection/
│
├── README.md
├── requirements.txt
├── Credit_Card_Fraud_Detection.ipynb
│
├── dataset/
│   └── train_transaction.csv
│
├── predictions/
│   └── final_fraud_predictions.csv
│
└── results/
    └── feature_importance.png
