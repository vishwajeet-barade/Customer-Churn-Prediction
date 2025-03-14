# Customer-Churn-Prediction

## Overview

This project focuses on predicting customer churn using machine learning techniques. The dataset, sourced from IBM Sample Data Sets, contains customer attributes such as demographic details, service subscriptions, contract types, payment methods, billing information, and churn status. The goal is to analyze customer behavior and develop strategies to improve customer retention.

## Confusion Matrix ## 

![image](https://github.com/user-attachments/assets/a92e2988-d126-44a3-9a15-5adf5e13c6e5)

## Error Analysis

Our Model Predict 0 well , but when churn is in actually 1 it not that much able to predict correct .

It may happen due to imbalance data .


## Oversampling & Performance Improvement

To address class imbalance, an oversampling technique was applied, increasing the F1-score for the churn class from 0.52 to 0.75. This suggests an improvement in correctly identifying customers likely to churn.

## Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

Machine Learning Models: (Specify the models used, e.g., Logistic Regression, Decision Tree, Random Forest, etc.)

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix



