# CSI_Week05
House Price Prediction using Data Preprocessing and Feature Engineering. Week 5 internship assignment @ Celebal Technologies.

This assignment explores the House Prices – Advanced Regression Techniques dataset from Kaggle to prepare it for machine learning models. The focus is on effective data preprocessing and creation of meaningful features to improve predictive performance.

The preprocessing involves:
Data Cleaning and Missing Value Imputation
Feature Engineering from domain-specific knowledge
Encoding of categorical features 
Feature Scaling using StandardScaler

This assignment was part of my internship at Celebal Technologies, Week 5 – with the goal of preparing high-quality data suitable for advanced regression models.

Dataset Info  
Source: Kaggle – House Prices: Advanced Regression Techniques  
Rows: 1460 (train), 1459 (test)  
Columns: 80+  
Target Variable: SalePrice (continuous variable in USD)

Key Features Used:  
LotFrontage – Linear feet of street connected to property  
OverallQual – Overall material and finish quality  
YearBuilt – Original construction year  
GrLivArea – Above ground living area (sq ft)  
GarageCars – Size of garage in car capacity  
TotalBsmtSF – Total square feet of basement area  
FullBath – Full bathrooms above grade  
TotRmsAbvGrd – Total rooms above grade  
Neighborhood – Physical locations within Ames city  
HouseAge, TotalSF, TotalBath – Engineered features

Preprocessing Techniques Applied  
Filling missing categorical values with 'None' (e.g., PoolQC, GarageType)  
Numerical imputation with 0 or group-wise median (e.g., LotFrontage)  
Feature creation (TotalSF, TotalBath, Porch area, Age of house)  
Ordinal encoding for quality-related features  
Label and One-hot encoding for nominal features  
Scaling numeric features using StandardScaler

Tools & Libraries  
Python 3.x  
Pandas  
NumPy  
Scikit-learn  
XGBoost (for model training)  
Matplotlib (optional visualization)

Output  
submission.csv – Predictions using trained model



