# Predictive Analysis of Customer Churn in Telecom
# Project Description

This project analyzes telecom customer data to understand factors influencing churn and predict which customers are likely to leave. Using exploratory data analysis (EDA), visualizations, and a Random Forest machine learning model, it provides insights for improving customer retention strategies.

# Dataset

 Source: Telecom customer churn dataset
 
 Contents: Customer demographics, service usage, contract details, payments, and churn information

# Files included:

telecom_customer_churn.csv – Main dataset

telecom_data_dictionary.csv – Data dictionary

telecom_zipcode_population.csv – Zip code population data

# Key Features / Analysis

Customer churn distribution and main reasons

Impact of contract type, monthly charges, tenure, age, and gender on churn

Service usage analysis (phone, internet, and value-added services)

Payment method analysis

Population group influence on churn

Machine learning model for churn prediction (Random Forest)

# Project Structure
Predictive-Analysis-of-Customer-Churn-in-Telecom/
├── notebook/
│   └── customer_churn
├── report/
│   └── Customer_Churn_Report.pdf
└── README.md

# Tools & Libraries

Python, Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Random Forest Classifier, train/test split, LabelEncoder)

# How to Run

Clone the repository

Open the notebook notebook/customer_churn1.ipynb in Google Colab or Jupyter Notebook

Ensure the data/ folder is in the same directory as the notebook

Run all cells to reproduce the analysis and model results

# Insights

Month-to-month contracts and higher monthly charges lead to higher churn

Customers without value-added services show higher churn

Competition and dissatisfaction are the main churn reasons

Random Forest model predicts churn effectively but is affected by class imbalance
