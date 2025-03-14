# Customer-Churn-Prediction

## Overview

This project focuses on predicting customer churn using machine learning techniques. The dataset, sourced from IBM Sample Data Sets, contains customer attributes such as demographic details, service subscriptions, contract types, payment methods, billing information, and churn status. The goal is to analyze customer behavior and develop strategies to improve customer retention.

## Confusion Matrix ## 

![image](https://github.com/user-attachments/assets/a92e2988-d126-44a3-9a15-5adf5e13c6e5)

## Error Analysis

Type I Error (False Positive): The model incorrectly predicts that a customer will churn when they actually stay.

Type II Error (False Negative): The model incorrectly predicts that a customer will stay when they actually churn. The model struggles to predict churn = 1 correctly, likely due to class imbalance in the dataset.

## Oversampling & Performance Improvement

To address class imbalance, an oversampling technique was applied, increasing the F1-score for the churn class from 0.52 to 0.75. This suggests an improvement in correctly identifying customers likely to churn.

## Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

Machine Learning Models: (Specify the models used, e.g., Logistic Regression, Decision Tree, Random Forest, etc.)

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix



