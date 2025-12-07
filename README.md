# End-to-End-Crop-Yield-Regression-Project
A Machine Learning–based Regression Analysis Project built using Python. This project implements multiple regression algorithms to predict a continuous target variable. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

### Project Overview
The goal of this project is to build and compare multiple regression models to identify the best-performing algorithm for predicting the target variable. The system evaluates each model using standard regression metrics and compares their performance.

### Tech Stack
Python,
Pandas, NumPy,
Matplotlib, Seaborn,
Scikit-Learn,
TensorFlow / Keras,
Jupyter Notebook.

### Approach
- Data Preprocessing:-
Loaded dataset using Pandas,
Renamed inconsistent columns,
Removed unnecessary columns,
Handled missing values,
Treated data entry errors and outliers,
Applied feature scaling,
Performed train–test split.

- Exploratory Data Analysis (EDA):-
Analyzed feature distributions,
Studied correlation between variables,
Identified multicollinearity,
Visualized important patterns and trends.

- Feature Engineering:-
Selected important features,
Converted data into numerical format,
Prepared final feature matrix for modeling,

- Regression Models Implemented:-
Linear Regression,
Polynomial Regression,
Ridge Regression (L2 Regularization),
Lasso Regression (L1 Regularization),
Elastic Net Regression,
Artificial Neural Network (ANN).

- Model Evaluation:-
Each model is evaluated using the following metrics:-
R² Score,
Root Mean Squared Error (RMSE).

- Model Deployment Using Joblib:-
The selected Linear Regression (Model 3) was successfully deployed using Joblib for model serialization. The trained model and preprocessing scaler were saved as .joblib files and later loaded for real-time prediction in the deployment environment.
