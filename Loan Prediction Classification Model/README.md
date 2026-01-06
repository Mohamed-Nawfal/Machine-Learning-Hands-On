"Loan Approval Prediction
This repository contains a comprehensive Python implementation for predicting loan approval status using machine learning. The project encompasses the entire data science pipeline, from exploratory data analysis (EDA) and data preprocessing to model training and evaluation.

Project Overview
The primary goal of this project is to automate the loan eligibility process based on customer details provided while filling out an online application form. These details include Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.

Dataset Features
The dataset includes the following key variables:

ApplicantIncome: Income of the primary applicant.

CoapplicantIncome: Income of the co-applicant.

LoanAmount: Loan amount in thousands.

Loan_Amount_Term: Term of the loan in months.

Credit_History: Credit history meets guidelines (1.0 or 0.0).

Gender, Married, Dependents, Education, Self_Employed: Categorical demographic and professional information.

Property_Area: Urban, Semi-Urban, or Rural.

Loan_Status: Target variable (Y/N).

Key Workflow
1. Data Preprocessing & Cleaning
Missing Value Imputation: Categorical values are filled using the Mode, while numerical values like LoanAmount are handled using the Median to account for skewness.

Outlier Removal: Used the Interquartile Range (IQR) method to eliminate extreme values in ApplicantIncome and CoapplicantIncome that could bias the model.

2. Exploratory Data Analysis (EDA)
Visualizations were created using Plotly to understand distributions and relationships:

Loan Approval Status distribution (Pie Chart).

Demographic breakdowns (Gender, Marital Status, Education).

Relationship analysis (e.g., Applicant Income vs. Loan Status) using box plots to identify data spread and outliers.

3. Model Training
Feature Engineering: Categorical variables were converted to numerical format using One-Hot Encoding.

Feature Scaling: Numerical features were normalized using StandardScaler to ensure the model treats all features equally.

Algorithm: A Support Vector Classifier (SVC) was trained on the processed data."
