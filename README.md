
# Employee Burnout Prediction

This project predicts employee burnout using machine learning techniques and deploys the solution as a Flask web application.

## About the Project
- Built ML pipeline with preprocessing, feature engineering, and XGBoost regression.
- Optimized hyperparameters using GridSearchCV.
- Flask web application deployed on PythonAnywhere.

## Dataset
- Employee data with attributes: Gender, Company Type, WFH Setup, Resource Allocation, Mental Fatigue Score, Designation.
- Target: Burn Rate (continuous variable).

## Methodology
1. Data Cleaning (duplicates removed, missing values imputed, outliers treated)
2. Feature Encoding and Scaling
3. Model Training:
   - Linear Regression
   - Ridge & Lasso
   - Random Forest
   - **XGBoost (Best Model)**
4. Evaluation (R², MAE, MSE)
