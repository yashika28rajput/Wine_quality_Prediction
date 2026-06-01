# Wine_quality_Prediction

A machine learning project that predicts wine quality using physicochemical properties such as acidity, alcohol content, sulphates, pH, and other chemical characteristics.

## Overview

The goal of this project is to analyze wine composition and build classification models capable of predicting wine quality. The project includes data preprocessing, exploratory data analysis, feature engineering, class balancing, model training, and performance evaluation.

## Dataset

The dataset contains various chemical properties of wine samples along with their quality ratings.

### Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

For classification, quality scores were grouped into quality categories to distinguish higher-quality wines from lower-quality wines.

## Workflow

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Feature Engineering
- Outlier Detection using Isolation Forest
- Feature Scaling
- Class Balancing using SMOTE
- Model Training and Comparison
- Cross Validation
- Feature Importance Analysis

## Models Implemented

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cross Validation Score
- Confusion Matrix

## Results

Some important findings from the analysis include:

- Alcohol content showed a strong relationship with wine quality.
- Sulphates were among the most influential positive indicators.
- Volatile acidity negatively affected wine quality.
- SMOTE helped address class imbalance and improve model learning.
- Ensemble models achieved better overall performance than individual models.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-Learn
- XGBoost

## Author

Yashika Rajput
