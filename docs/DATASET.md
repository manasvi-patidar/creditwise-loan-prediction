# Dataset Description

## 1. Overview

The CreditWise project uses historical loan application
data to predict whether a loan application should be
Approved or Rejected.

Each row in the dataset represents an individual loan
applicant and contains personal, financial, employment,
and credit-related information.

## 2. Dataset Features

| Column             | Description                             |
| ------------------ | --------------------------------------- |
| Applicant_ID       | Unique applicant ID                     |
| Applicant_Income   | Monthly income of applicant             |
| Coapplicant_Income | Monthly income of co-applicant          |
| Employment_Status  | Salaried / Self-Employed / Business     |
| Age                | Applicant age                           |
| Marital_Status     | Married / Single                        |
| Dependents         | Number of dependents                    |
| Credit_Score       | Credit bureau score                     |
| Existing_Loans     | Number of already running loans         |
| DTI_Ratio          | Debt-to-Income ratio                    |
| Savings            | Savings balance                         |
| Collateral_Value   | Value of collateral provided            |
| Loan_Amount        | Loan amount requested                   |
| Loan_Term          | Loan duration (months)                  |
| Loan_Purpose       | Home / Education / Personal / Business  |
| Property_Area      | Urban / Semi-Urban / Rural              |
| Education_Level    | Graduate / Postgraduate / Undergraduate |
| Gender             | Male / Female                           |
| Employer_Category  | Govt / Private / Self                   |
| Loan_Approved      | 1 = Approved, 0 = Rejected              |

## 3. Target Variable

**Loan_Approved**

This is the target variable used for supervised
classification.

- 1 → Loan Approved
- 0 → Loan Rejected

## 4. Problem Type

- Machine Learning Type: Supervised Learning
- Task: Binary Classification
- Target: Loan_Approved

## 5. Dataset Usage

The dataset will be used for:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- Loan Approval Prediction
