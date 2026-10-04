# CreditFair: AI-Based Loan Default Prediction and Fair Lending Assessment System

## 1. Project Overview

CreditFair is a machine learning project designed to analyze loan applications and predict loan repayment outcomes.

The project performs:

- Data understanding and preprocessing
- Linear Regression for continuous loan amount prediction
- Logistic Regression for loan default classification
- Fairness assessment across home ownership groups
- Model prediction using a saved machine learning model
- Data visualization and result generation

The project is developed as part of an academic Machine Learning project.

---

## 2. Objectives

The main objectives of CreditFair are:

1. Understand and preprocess loan application data.
2. Implement Linear Regression as required for the project.
3. Build a classification model to predict loan status.
4. Evaluate the classification model using appropriate metrics.
5. Assess differences in model behavior across home ownership groups.
6. Save the trained classification model for prediction.
7. Generate visualizations and reports for analysis.

---

## 3. Dataset

The project uses a Kaggle Loan Default Prediction dataset.

The training dataset contains:

- **27,003 rows**
- **47 columns**

The dataset includes information such as:

- Loan amount
- Interest rate
- Employment length
- Annual income
- Home ownership
- Verification status
- Loan purpose
- Debt-to-income ratio
- Credit history information
- Loan status

The raw dataset is intentionally not included in the GitHub repository.

Expected dataset location:

```text
data/raw/loan_train.csv