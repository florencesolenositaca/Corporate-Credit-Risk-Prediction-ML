# 💳 Corporate Credit Risk Prediction Using Machine Learning

### Machine Learning & Predictive Analytics | 2026

Developed by **Florence Elaine G. Soleño**

---

## Project Overview

Assessing a company's creditworthiness is an important part of financial decision-making. However, businesses with similar financial profiles may have different levels of credit risk, making it difficult to evaluate their financial stability using individual financial indicators alone.

This project applies **machine learning regression techniques to predict corporate credit risk scores** based on financial performance, operational characteristics, historical borrowing behavior, and regional factors.

By comparing multiple regression models, the project aims to identify the most reliable approach for estimating credit risk and determine which company characteristics are most strongly associated with financial instability.

The goal is to support **data-driven credit risk assessment, more consistent lending decisions, and improved financial portfolio management.**

## Dataset Information

This project uses a hypothetical corporate credit risk dataset containing financial, operational, and contextual information about businesses.

- **Objective:** Predict a company's CreditRiskScore
- **Unit of Analysis:** Individual company records
- **Target Variable:** CreditRiskScore (continuous numerical value)
- **Predictor Variables:** Financial performance, company characteristics, borrowing history, collateral, and contextual factors

### Key Dataset Features

- **Financial Performance:** Annual Revenue, Profit Margin
- **Company Profile:** Number of Employees, Years in Operation
- **Credit History:** Previous Defaults, Average Monthly Debt Obligation, Current Loan Amount
- **Asset Backing:** Collateral Value
- **Financial Reporting:** Financial Statement Quality
- **Contextual Factors:** Industry and Region

## Machine Learning Implementation

### Regression Models

Five model types are considered in this project:

- **Ridge Regression** – Applies L2 regularization to reduce coefficient instability.
- **LASSO Regression** – Uses L1 regularization to shrink coefficients and support feature selection.
- **Elastic Net Regression** – Combines L1 and L2 regularization.
- **Random Forest Regressor** – Uses an ensemble of decision trees to capture complex, nonlinear relationships.

### Model Evaluation

Model performance is assessed using:

- **Root Mean Squared Error (RMSE)** – Measures prediction error while penalizing larger deviations.
- **Cross-Validation RMSE** – Evaluates model performance across multiple training folds.
- **Training RMSE** – Measures prediction error on the training dataset.
- **Testing RMSE** – Evaluates predictive accuracy on unseen data.

### Predictive Analysis

- Identification of key financial and operational factors associated with credit risk
- Comparison of regularized linear regression and ensemble-based approaches
- Evaluation of model generalization and predictive reliability
- Interpretation of relationships between company characteristics and CreditRiskScore

## Technologies Used

Python – Machine learning and predictive analysis

Jupyter Notebook – Model development and experimentation

Pandas – Data manipulation and preprocessing

NumPy – Numerical computations

Scikit-learn – Regression modeling, preprocessing, and model evaluation

Matplotlib / Seaborn – Statistical analysis and data visualization

🌍 Project Significance

This project demonstrates how machine learning can support financial risk assessment and creditworthiness evaluation by transforming company-level data into predictive insights.

By analyzing financial indicators, borrowing history, and operational characteristics, the project explores how predictive models can provide a more consistent basis for assessing corporate credit risk.

The findings highlight the potential of machine learning to support informed lending decisions, early identification of high-risk companies, and more effective capital allocation.

