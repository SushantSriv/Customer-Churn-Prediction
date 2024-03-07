# Churn Prediction Analysis for Retail Banking

## Introduction
This repository contains the machine learning models and analysis for predicting customer churn in retail banking. The objective is to leverage data to predict whether a customer will stay with the bank or leave (churn) with high accuracy.

## Dataset
The dataset used for this analysis is a dummy dataset with 10,000 rows containing various demographic and banking information for customers, with no missing values.

## Analysis Overview
- **Exploratory Data Analysis (EDA)**: To understand the distribution and relationships within the data.
- **Feature Engineering**: Creation of additional features like Credit Score to Age Ratio and Balance to Salary Ratio for better insights.
- **Class Imbalance Handling**: Use of SMOTE (Synthetic Minority Over Sampling Technique) to balance the dataset.
- **Model Building**: Development of multiple predictive models including SVM (with and without SMOTE), Random Forest, and Neural Networks.
- **Model Evaluation**: Models are evaluated based on their accuracy and the rate of false negatives.
- **Inferences**: Derived from plots and model outcomes to understand the characteristics of churning and remaining customers.

## Results
The Neural Network model achieved the best performance with an accuracy of around 86% and a false negative rate of 2.11%, indicating a high predictive capability for actual churn events.

## Recommendations
### Product Portfolio Evaluation
- Assess and refine product offerings.
  
### Credit Score and Tenure Analysis
- Further explore the lack of distinctions in credit score and tenure between churned and retained customers through customer feedback surveys.

### Balance Retention Strategies
- Develop personalized strategies to retain customers with significant account balances.

### Regular Monitoring and Adaptation
- Implement continuous monitoring of strategy effectiveness.

### Collaboration with Customer Support
- Enhance the collaboration between data analysis teams and customer support.

### Promotion of Financial Literacy
- Launch educational campaigns for customers to make informed financial decisions.

### Incentivize Customer Feedback
- Encourage and utilize customer feedback for improvements.

### Cross-Functional Team Collaboration
- Promote collaboration between various teams to enhance customer satisfaction and retention.
