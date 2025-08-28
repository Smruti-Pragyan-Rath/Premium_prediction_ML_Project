# Annual Premium Price Prediction (Machine Learning Project)

# Project Overview

This project is a Machine Learning model to predict the annual premium price of an insurance policy based on customer-related features such as age, number of dependents, income level, and lifestyle attributes.

The goal is to help **insurance companies** and analysts make data-driven pricing decisions and provide personalised offers to customers.

# Features

1. Exploratory Data Analysis (EDA) with visualisations

2. Data preprocessing: handling missing values, encoding categorical variables, and feature scaling

3. **Model training** with **Linear Regression, Ridge, Lasso, XGBoost** (and comparison of results)

4. Performance evaluation with metrics such as RMSE, MAE, R²

5. Deployed an interactive Streamlit web app to input features and get premium predictions

# Tech Stack

Python (Pandas, NumPy, Scikit-learn, XGBoost)

Streamlit (deployment & UI)

Matplotlib & Seaborn (EDA and visualization)

GitHub (Version control)

# Dataset

Contains customer information and insurance details

Key features: age, gender, region, dependents, income_level, smoking_status, genetic risk, etc.

Target variable: annual_premium_price

# How It Works

Data Preprocessing → Clean & transform raw data

Model Training → Train ML algorithms and tune hyperparameters

Evaluation → Compare models and choose best performer

Deployment → Serve predictions via Streamlit app

📈 Results

Best performing model: XGBoost (R² = 3.67)

**Linear Regression provided a strong baseline**

Streamlit app allows users to **test predictions with custom inputs**
