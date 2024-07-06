# Predicting Bank Customer Churn Using Machine Learning Techniques

This repository contains a project that uses machine learning to develop a predictive model for bank customer churn. The project includes data loading, preprocessing, addressing class imbalance, training an SVM classifier, and optimizing it with hyperparameter tuning to enhance prediction accuracy.

## Project Overview

1. **Data Loading and Exploration**:
   - Load the dataset and perform initial exploratory data analysis (EDA) to understand the data.

2. **Data Preprocessing**:
   - Encode categorical variables.
   - Create a new feature to indicate zero balance.
   - Define the target variable (Churn) and feature variables.

3. **Addressing Class Imbalance**:
   - Use random undersampling and oversampling techniques to balance the classes.

4. **Data Splitting and Feature Scaling**:
   - Split the data into training and testing sets.
   - Apply feature scaling to normalize the data.

5. **Model Training**:
   - Train a Support Vector Machine (SVM) classifier on raw, undersampled, and oversampled data.

6. **Model Evaluation**:
   - Evaluate the performance using confusion matrices and classification reports.

7. **Hyperparameter Tuning**:
   - Optimize the SVM classifier using grid search.
   - Compare the final model's performance across different sampling strategies to demonstrate improvements in prediction accuracy.
