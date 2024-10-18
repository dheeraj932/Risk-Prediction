# Risk Prediction on Prudential Life Insurance

## Project Overview

This project aims to enhance risk evaluation in life insurance through predictive analytics, focusing on categorizing insurance risks using historical data. The project leverages machine learning models to improve the accuracy and transparency of risk classification, crucial for informed decision-making in insurance claims.

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Setting](#problem-setting)
- [Objective](#objective)
- [Data Sources](#data-sources)
- [Data Exploration](#data-exploration)
- [Data Pre-processing](#data-pre-processing)
- [Modeling Approach](#modeling-approach)
- [Performance Evaluation](#performance-evaluation)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Contributors](#contributors)

## Problem Setting

In the insurance sector, accurately predicting risk is essential for efficient operations and profit generation. Traditionally, this prediction relied on manual underwriting methods using statistical equations and life expectancy tables. With advancements in data science, machine learning approaches offer a streamlined and precise risk evaluation method. This project applies these technologies to life insurance, where accurate risk classification is vital.

## Objective

The goal is to enhance risk evaluation in life insurance by categorizing risks using historical data. The project aims to identify the most effective predictive model for this task while improving the clarity and comprehensibility of machine learning models for stakeholders.

## Data Sources

The dataset used is the Prudential Life Insurance Assessment from Kaggle, featuring 59,381 rows and 128 columns. It includes a mix of nominal, continuous, and discrete variables, providing a robust foundation for analyzing and predicting life insurance risk factors.

## Data Exploration

Exploratory Data Analysis (EDA) was conducted to understand the dataset's structure and features. Key observations include:
- Class 8 has the highest frequency in the response variable.
- The distribution is skewed, with some classes occurring more frequently than others.

## Data Pre-processing

Key steps included:
- Handling missing values by removal or imputation.
- Identifying and treating outliers using the Interquartile Range (IQR) method.
- Encoding categorical variables using one-hot encoding.
- Applying dimensionality reduction techniques like PCA when necessary.

## Modeling Approach

Several machine learning models were evaluated, including:
1. **Logistic Regression**: Provides a probabilistic perspective for binary classification.
2. **Decision Tree**: Offers intuitive decision-making with visualizable rules.
3. **Random Forest**: Combines multiple trees to improve accuracy and reduce overfitting.
4. **XGBoost**: Utilizes gradient boosting for enhanced performance.
5. **Support Vector Machine (SVM)**: Constructs optimal hyperplanes for classification.
6. **Neural Network**: Captures complex patterns through layered architecture.

## Performance Evaluation

The models were evaluated based on metrics such as accuracy, F-score, precision, recall, and ROC AUC. Key findings include:
- Random Forest achieved the highest accuracy of 96%.
- XGBoost also performed well with an accuracy close to Random Forest.
- Logistic Regression had lower performance compared to tree-based models.

## Conclusion and Future Work

Random Forest emerged as the best model for this dataset. Future work includes exploring advanced neural network architectures like RNNs or CNNs and enhancing feature engineering techniques to improve model performance further.

## Contributors

- Vikramadithya Pabba
- Dheeraj Kumar Goli
