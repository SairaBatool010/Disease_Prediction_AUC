# Medical Condition Prediction - IML Fall 2024 Challenge 1

## Overview
This repository contains the code and methodology for predicting the presence of a certain medical condition using a dataset from the **IML Fall 2024 Challenge 1** on Kaggle. The goal is to predict whether a medical condition is present based on a set of features provided in the dataset. The model's performance is evaluated based on the **AUC (Area Under the ROC Curve)** of the positive class.

The model has achieved a score of **0.95929** after extensive exploration, hyperparameter tuning, and testing various algorithms to find the optimal solution.

Dataset link: [IML Fall 2024 Challenge 1 Dataset](https://www.kaggle.com/competitions/iml-fall-2024-challenge-1/data)

## Objective
The challenge requires the development of a classifier that predicts the presence or absence of a medical condition. The performance of the classifier is assessed using the **AUC metric** on the ROC curve for the positive class, with higher scores indicating better model performance.

## Approach

### 1. Data Exploration & Preprocessing:
- Analyzed and cleaned the dataset by handling missing values, encoding categorical features, and scaling numerical features where necessary.
- Performed exploratory data analysis (EDA) to understand the distribution of features and detect any correlations or patterns in the data.

### 2. Model Selection & Evaluation:
- Tried different machine learning algorithms including **Logistic Regression**, **Random Forest**, **Gradient Boosting**, and **XGBoost**.
- Employed **cross-validation** to assess the model’s generalization performance.
- Implemented **grid search** and **random search** for hyperparameter tuning to find the best performing model.
- Evaluated models using **AUC-ROC curve** and selected the one with the best AUC score for further refinement.

### 3. Hyperparameter Tuning:
- Tuned hyperparameters for models like **Random Forest** and **Gradient Boosting**, including the number of trees, depth, learning rate, and regularization.
- Optimized feature selection and model regularization techniques to prevent overfitting.

### 4. Final Model:
- After extensive experimentation, the final model achieved an **AUC score of 0.95929**.
- The model incorporates techniques such as **feature engineering**, **ensemble methods**, and **hyperparameter optimization**.

### 5. Model Evaluation:
- Evaluated the model on the test set using **AUC-ROC curve** 
