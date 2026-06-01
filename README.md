# Wine_quality_Prediction
The project predicts quality of wine based on their chemical composition.
Wine Quality Prediction

This project focuses on predicting wine quality using machine learning techniques based on physicochemical properties such as acidity, alcohol content, sulphates, pH, and other chemical characteristics.

The workflow covers data preprocessing, exploratory data analysis, feature engineering, handling class imbalance, model training, and performance evaluation. Multiple machine learning algorithms were trained and compared to identify the most effective approach for wine quality classification.

Dataset

The dataset contains various chemical properties of wine samples along with their quality ratings.

Features include:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol

For classification, wine quality scores were grouped into quality categories to distinguish higher-quality wines from lower-quality wines.

Project Workflow
Data Cleaning and Preprocessing
Exploratory Data Analysis
Correlation Analysis
Feature Engineering
Outlier Detection using Isolation Forest
Feature Scaling
Class Balancing using SMOTE
Model Training and Comparison
Cross Validation
Feature Importance Analysis
Models Used
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
XGBoost
Evaluation Metrics

Model performance was evaluated using:

Accuracy
Precision
Recall
F1-Score
Cross Validation Score
Confusion Matrix
Key Observations
Alcohol content showed a strong relationship with wine quality.
Sulphates were among the most influential positive indicators.
Volatile acidity negatively affected wine quality.
Class imbalance was addressed using SMOTE to improve model learning.
Ensemble methods demonstrated stronger performance compared to individual models.
Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-Learn
XGBoost

Author

Yashika Rajput
