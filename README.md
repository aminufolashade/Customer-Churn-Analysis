# Customer-Churn-Analysis
It is an End‑to‑end customer churn analysis using Python, covering data cleaning, EDA, feature engineering, and machine learning models. Built and evaluated Logistic Regression and Random Forest models with ROC‑AUC and F1 metrics to identify at‑risk customers and support data‑driven retention strategies. This project explores customer churn behavior in the telecommunications industry using Python and machine learning. The goal is to identify churn drivers and build predictive models that classify customers at risk of leaving the company.

## Objectives:
- Analyze customer behavior and churn patterns
- Identify key factors influencing churn
- Build and compare predictive models
- Evaluate models using Accuracy and ROC‑AUC
- Generate business insights for retention strategies

## Dataset:
- Records: 7,043 customers
- Features: Demographics, services, billing, contracts
- Target: Churn (Yes / No)

## Tools & Libraries:
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit‑learn
- imbalanced‑learn

## Workflow:
1. Data cleaning & preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering  
4. Model training (Logistic Regression, Random Forest)  
5. Model evaluation & comparison  
6. Cross‑validation  
7. Model export for deployment  

## Key Insights:
- Month‑to‑month contracts have the highest churn rate
- Higher monthly charges increase churn risk
- Fiber optic internet users churn more than DSL users
- Longer tenure significantly reduces churn

## Model Performance:
- **Best Model:** Random Forest Classifier
- **Accuracy:** ~81%
- **ROC‑AUC:** ~0.84

Logistic Regression achieved slightly higher AUC during cross‑validation, while Random Forest captured nonlinear feature interactions more effectively.

## Model Files:
- `random_forest_churn_model.pkl`
- `logistic_regression_churn_model.pkl`
