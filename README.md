# bank-churn-prediction-ml
A machine learning project to predict bank customer churn using models like LightGBM, XGBoost, Random Forest, and CatBoost. Includes data preprocessing, model evaluation, and hyperparameter tuning to support customer retention strategies in the banking sector.
# Bank Churn Prediction Using Machine Learning
This project aims to predict customer churn in the banking sector using various machine learning algorithms. Churn refers to the scenario when a customer stops using the bank's services. Predicting churn is crucial for banks to retain valuable customers and reduce financial loss.

## 🔍 Problem Statement
Identify customers who are likely to leave the bank based on historical data and customer attributes.

## 📊 Dataset
- **Source:** [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)
- **Target Variable:** `Churn`
- **Features Include:** `Customer ID`, `Credit Score`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `Number of Products`, `Credit Card`, `Active Member`, `Estimated Salary`

## 🧪 Data Preprocessing
- Label Encoding (Gender)
- One-Hot Encoding (Geography)
- Feature Scaling using Z-Score
- Correlation Matrix Analysis
- Class imbalance handling

## 🤖 Models Used
- LightGBM Classifier
- XGBoost Classifier
- Random Forest Classifier
- CatBoost Classifier

## ⚙️ Model Tuning
- Hyperparameter tuning using `GridSearchCV`
- Comparison of model performance based on precision, recall, and F1-score

## ✅ Best Performing Model
- **CatBoost Classifier** with hyperparameter tuning
- Chosen for its high recall on churn class and balanced F1-score

## 📌 Key Learnings
- Model evaluation on imbalanced datasets
- Practical experience with multiple classifiers
- Importance of recall in churn prediction use cases

## 📁 Project Structure
