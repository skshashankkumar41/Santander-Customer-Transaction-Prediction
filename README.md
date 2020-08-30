# Santander Customer Transaction Prediction
## Blog - https://medium.com/@skshashankkumar41/santander-customer-transaction-prediction-44ab30d2236c
## Business Problem 
The aim of Santander bank is to predict which customers will make a specific transaction in the future that means given particular features of customers we have to determine whether this customer will make a transaction or not. 
## Business Constraints 
* Interpretability is essential as the bank should know the reasons for that specific transaction.
* No low latency Requirement as we want to know will this user will make a prediction in the future so we can wait for the prediction little bit.
* We also need the probability of each class belonging.
## ML Problem Formulation
* It is a binary classification task as we want to predict whether the transaction will occur or not.
* To solve this problem we will be using data from Kaggle's Santander Customer Transaction Prediction Post. https://www.kaggle.com/c/santander-customer-transaction-prediction/data
* Performance Metric - ROC-AUC Score (Area under the ROC Curve)
## Data
* We are provided with an anonymized dataset of 200,000 data points containing numeric feature variables, the binary target column, and a string ID_code column. All the data points are real-valued. As we don't know anything about features it makes it very difficult for feature engineering and feature selection.


