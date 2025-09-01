# California_House_Prediction

# Overview

This project predicts house prices in California using Linear Regression, Ridge, and Lasso Regression. It demonstrates a complete ML workflow including data preprocessing, model training, cross-validation, and evaluation.

# Dataset

Source: California Housing dataset (from sklearn.datasets)

Features: Median income, housing age, rooms, population, latitude, longitude, etc.

Target: Median house value (Price)

# Methodology

# Data Loading & Exploration

Fetched dataset from sklearn.datasets

Converted to pandas.DataFrame and added target column

# Preprocessing

Split into features (X) and target (y)

Train-test split (37% test size, random_state=42)

# Modeling

Linear Regression

Ridge Regression

Lasso Regression

# Evaluation Metrics

Mean Squared Error (MSE)

Cross-validation (5-fold)

# Results

Compared performance of Linear, Ridge, and Lasso

Cross-validation scores analyzed

Visualizations created with Matplotlib & Seaborn
