# Adult Income Binary Classification Project
## Overview
This project focuses on predicting whether an individual’s income exceeds $50,000 per year based on various features. We use a binary classification model with Logistic Regression.

## Dataset
Dataset Name: Adult Income Dataset
Source: UCI Machine Learning Repository
Description: The dataset contains information about individuals, including features like age, education, occupation, marital status, and more. The target variable is whether the income exceeds $50,000 (1) or not (0).

## Data Preprocessing
Encoding: The dataset was encoded into binary values (0 and 1).
Wrangling: A custom wrangling function was applied to handle missing values, outliers, and other data quality issues.
Feature Engineering:
Categorical Features: OneHotEncoder was used to convert categorical features into binary vectors.
Numerical Features: StandardScaler normalized numerical features to have zero mean and unit variance.

## Model
Algorithm: Logistic Regression
Training and Testing:
The dataset was split into training and testing sets.
Logistic Regression was trained on the training data.
Model performance was evaluated using the confusion matrix.

## Results
## Confusion Matrix:
+-------------------+-------------------+

| True Positive (TP)| False Negative (FN)|

+-------------------+-------------------+

| False Positive (FP)| True Negative (TN) |

+-------------------+-------------------+

Accuracy: (TP + TN) / (TP + TN + FP + FN)

Precision: TP / (TP + FP)

Recall (Sensitivity): TP / (TP + FN)

F1-Score: 2 * (Precision * Recall) / (Precision + Recall)

## Conclusion
The Logistic Regression model achieved satisfactory results in predicting income levels.

Further optimization and feature engineering can be explored to enhance model performance.
