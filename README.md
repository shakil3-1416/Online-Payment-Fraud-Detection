# Online-Payment-Fraud-Detection
This project aims to identify fraudulent and non-fraudulent online payments using a dataset from Kaggle. The dataset includes 10 variables detailing transaction information, such as type, amount, and balances, to help detect fraudulent activities. The study focuses on analyzing historical data to improve fraud detection.
# Project Overview
Online payments have become the most popular transaction method globally, but this rise in digital transactions has also led to an increase in payment fraud. The objective of this project is to develop a model that can accurately identify fraudulent and non-fraudulent transactions, thereby enhancing security in online payments.

# Dataset Description
The dataset used in this project is sourced from Kaggle and contains historical transaction data that can be leveraged to detect fraud. It includes the following 10 variables:

step: Represents the unit of time in hours since the start of the data collection period.
type: The type of online transaction (e.g., transfer, payment).
amount: The amount involved in the transaction.
nameOrig: The ID of the customer initiating the transaction.
oldbalanceOrg: The balance of the sender before the transaction.
newbalanceOrig: The balance of the sender after the transaction.
nameDest: The ID of the recipient of the transaction.
oldbalanceDest: The balance of the recipient before the transaction.
newbalanceDest: The balance of the recipient after the transaction.
isFraud: A binary variable indicating whether the transaction was fraudulent.

# Project Objectives
Data Exploration & Preprocessing: Clean and explore the dataset to understand the distribution of variables and identify any anomalies or patterns.
Feature Engineering: Create new features or transform existing ones to improve the predictive power of the model.
Model Development: Implement various machine learning models to classify transactions as fraudulent or non-fraudulent.
Model Evaluation: Assess the performance of the models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Fraud Detection Strategy: Develop a strategy based on the model’s output to minimize false positives while effectively identifying fraudulent transactions.

#Key Features
Comprehensive Data Analysis: In-depth analysis of transaction data to uncover trends and correlations that are indicative of fraud.
Machine Learning Models: Implementation of multiple models, including logistic regression, decision trees, random forests, and gradient boosting, to detect fraud.
Feature Importance: Identification of the most significant variables that contribute to predicting fraudulent activities.
Model Tuning: Hyperparameter tuning to optimize model performance and reduce overfitting.
