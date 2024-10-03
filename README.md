# Customer Churn Prediction

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
Customer churn prediction is an essential task for businesses aiming to retain their customers. This project aims to build a predictive model to identify customers likely to churn using various machine learning techniques. 

### Objective
The main objective of this project is to build a predictive model that can help the telecom company identify customers who are likely to churn. By understanding the factors contributing to churn, the company can implement targeted retention strategies.

## Dataset
The dataset used in this project is sourced from [source or reference link]. It contains information about customers, including demographic data, service usage, and churn status. The main features include:

- `customerID`: Unique identifier for each customer
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen (1 or 0)
- `Partner`: Whether the customer has a partner (Yes or No)
- `Dependents`: Whether the customer has dependents (Yes or No)
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has a phone service (Yes or No)
- `MultipleLines`: Whether the customer has multiple lines (Yes, No, No phone service)
- `InternetService`: Customer's internet service provider (DSL, Fiber optic, No)
- `OnlineSecurity`: Whether the customer has online security (Yes, No, No internet service)
- `OnlineBackup`: Whether the customer has online backup (Yes, No, No internet service)
- `DeviceProtection`: Whether the customer has device protection (Yes, No, No internet service)
- `TechSupport`: Whether the customer has tech support (Yes, No, No internet service)
- `StreamingTV`: Whether the customer has streaming TV service (Yes, No, No internet service)
- `StreamingMovies`: Whether the customer has streaming movies service (Yes, No, No internet service)
- `Contract`: The type of contract (Month-to-month, One year, Two year)
- `PaperlessBilling`: Whether the customer uses paperless billing (Yes or No)
- `PaymentMethod`: The customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- `MonthlyCharges`: The amount charged to the customer monthly
- `TotalCharges`: The total amount charged to the customer
- `Churn`: Whether the customer has churned (Yes or No)

## Machine Learning Algorithms Used
In this project, several machine learning algorithms were implemented to predict customer churn:
1. **Logistic Regression**: A statistical method for binary classification.
2. **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies data points based on the class of their neighbors.
3. **Support Vector Machine (SVM)**: A supervised learning model that finds the optimal hyperplane for classification tasks.
4. **Random Forest**: An ensemble learning method that constructs multiple decision trees and outputs the mode of their predictions.
5. **XGBoost**: An optimized gradient boosting library designed for speed and performance.
6. **AdaBoost**: An ensemble technique that combines the predictions of several base estimators to improve robustness.
7. **Gradient Boosting Classifier**: An ensemble technique that builds models in a stage-wise fashion and generalizes them by allowing optimization of arbitrary differentiable loss functions.
8. **Decision Tree Classifier**: A tree-like model used for classification and regression tasks, representing decisions and their possible consequences.

## Results
The model performances were evaluated using various metrics, including accuracy, confusion matrix, and classification report, allowing us to compare the effectiveness of each algorithm in predicting churn.
