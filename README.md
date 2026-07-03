# Predicting Rainfall Using Machine Learning Classification Algorithms

# Project Overview

This project predicts whether it will rain the next day using historical Australian weather data. Multiple machine learning classification algorithms were developed and evaluated on both imbalanced and balanced datasets to identify the most accurate prediction model. The workflow includes data preprocessing, missing value imputation, outlier detection, feature selection, model training, and performance evaluation.

# Objectives
-Predict rainfall occurrence using weather attributes.
-Compare model performance on balanced vs imbalanced datasets.
-Improve prediction accuracy through preprocessing and feature engineering.

# Dataset
-Australian Weather Dataset
-Source: Kaggle
-Target Variable: RainTomorrow (Yes/No)

# Data Preprocessing
-Missing Value Imputation (MICE)
-Outlier Removal (IQR)
-Label Encoding
-Feature Selection
-Handling Class Imbalance

# Machine Learning Models
-Logistic Regression
-Decision Tree
-Random Forest
-K-Nearest Neighbors (KNN)
-Artificial Neural Network

# Evaluation Metrics
-Accuracy
-Precision
-Recall
-F1 Score
-Confusion Matrix

# Technologies Used
-Python
-Pandas
-NumPy
-Scikit-learn
-Matplotlib
-Seaborn

# Results

Random Forest achieved the highest performance after balancing the dataset, outperforming the other classification models across multiple evaluation metrics.
