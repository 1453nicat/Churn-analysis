# Churn-analysis
Telco Customer Dataset using LinearSVC, RandomForestClassifier, XGBoost, and LighGBM algorithms

This project aims to analyze and predict customer churn in a telecom company using machine learning techniques. Customer churn refers to when customers stop doing business with a company. By accurately predicting churn, telecom companies can take proactive measures to retain customers, thereby improving revenue and customer satisfaction.

Target variable: Churn (Yes/No)

# Project Workflow
1. Data Preprocessing
2. Exploratory Data Analysis (EDA).
3. Model Implementation
  a. Random Forest Classifier: ensemble learning method that uses multiple decision trees. Tuned hyperparameters: n_estimators, max_depth, min_samples_split, etc.
  b. XGBoost: gradient Boosting framework optimized for speed and performance. Tuned hyperparameters: learning_rate, max_depth, n_estimators, etc.
  c. LightGBM: gradient Boosting framework that handles large datasets efficiently. Tuned hyperparameters: num_leaves, learning_rate, max_depth, etc.
  d. LinearSVC: support Vector Machine for linear classification. Tuned hyperparameters: C, loss, max_iter, etc.
4. Model Evaluation

# Libraries
- zipfile, pandas and numpy: for data manipulation
- missingno: for null data visualization
- matplotlib and seaborn: fro data visualization
- sklearn: for machine learning
- lazypredict
- xgboost, lightgbm
