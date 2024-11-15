# Telecom Customer Churn Prediction

This project uses a telecom churn dataset from Kaggle to predict customer churn using machine learning classification models. It investigates the effect of feature scaling on model performance and evaluates results on an imbalanced dataset.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
4. [Machine Learning Models](#machine-learning-models)


## Project Overview
Customer churn prediction helps businesses understand and address customer attrition.  
- **Dataset**: Telecom churn dataset from Kaggle.  
- **Challenge**: The dataset is imbalanced, with fewer churned customers compared to non-churned ones.  
- **Objective**: Compare the performance of classification models with and without feature scaling.  
- **Metrics**: Accuracy, confusion matrix, and recall.

## Dataset
- Contains information about customer demographics, services, and payment details.  
- **Target Variable**: `Churn` (1 = churned, 0 = stayed).

## Exploratory Data Analysis
Key visualizations include:  
- **Churn Rate per Feature**: Understanding how features correlate with churn.  
- **Bar Plot**: Distribution of churned, stayed, and joined customers.  
- **Heatmap**: Correlation matrix of features to identify relationships.  

## Machine Learning Models
This project applies machine learning classification models to predict customer churn. Two approaches were explored:
1. **Without Feature Scaling**  
2. **With Feature Scaling**

### Steps Followed
1. Data preprocessing to handle missing values, categorical variables, and scaling where required.
2. Applied the following classification algorithms:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - Decision Tree
3. Evaluated the models using:
   - **Accuracy**: Measures overall model correctness.
   - **Confusion Matrix**: Summarizes prediction results for each class.
   - **Recall**: Focuses on identifying churned customers (positive class).

