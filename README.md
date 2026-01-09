# Project Background
Banks have extensive customer data, but raw datasets often contain missing values, inconsistencies, or irrelevant information.  
This project focuses on preparing bank customer data for predictive modeling, aiming to:
- Identify key trends in customer demographics and account behavior  
- Clean and transform the dataset to ensure consistency  
- Create a structured dataset ready for machine learning models  
The goal is to support churn prediction, enabling banks to improve retention strategies and customer engagement.
# Bank Customer Data Prep_Python
**Project Type:** Python Data Cleaning & Exploration + Machine Learning Prep  
**Dataset:** Bank Customer Churn (10,000 European bank accounts)  
**Tools:** Python (pandas, numpy, matplotlib, seaborn), Jupyter Notebook, Power BI / Tableau # Data Structure
# Data Structure
The dataset contains customer account information with the following key columns: <a href = "https://github.com/mizanur-analytics/bank-customer-prep-python/blob/main/Bank_Churn_Messy.xlsx">bank_customer_churn</a>
| Column           | Description                               |
|------------------|-------------------------------------------|
| CustomerID       | Unique identifier for each customer       |
| Surname          | Customer’s last name                       |
| CreditScore      | Customer credit score                      |
| Geography        | Country of residence                       |
| Gender           | Male/Female                                |
| Age              | Customer age                               |
| Tenure           | Number of years with the bank              |
| Balance          | Account balance                            |
| NumOfProducts    | Number of bank products held              |
| HasCrCard        | Customer has credit card (0/1)            |
| IsActiveMember   | Active membership status (0/1)            |
| EstimatedSalary  | Customer’s estimated annual salary        |
| Exited           | Whether customer churned (target variable)|

Each row represents one customer. Data may include missing values, duplicates, or inconsistent entries.
# Business Questions
- Which customers are at risk of leaving the bank?  
- Are there patterns in demographics, geography, or product usage that predict churn?  
- How can account balances, tenure, and activity influence customer retention?  
- What transformations are required to prepare the data for machine learning?  
# Process
1. Loaded the dataset into Python (pandas)  
2. Performed exploratory data analysis (EDA) to understand distributions and anomalies  
3. Handled missing values and replaced inconsistent entries  
4. Removed duplicates and irrelevant columns  
5. Encoded categorical variables for machine learning  
6. Scaled numerical features for modeling  
7. Visualized patterns in customer behavior and churn  

# Executive Summary
## Overview of Findings
- Certain age groups and geographies show higher churn risk  
- Customers with fewer products or inactive accounts are more likely to leave  
- Higher balances and longer tenure reduce churn probability  
## Trends
- Churn clusters around specific demographics  
- Inactive members and low engagement correlate with exiting  
## Product Insights
- Products like credit cards and multiple accounts influence retention  
- Salary alone is not a strong churn predictor  
*(Dashboard screenshot placeholder)*

# Project Insights
## Quantified Value
- Data cleaning reduced missing values from 15% to near 0%  
- Categorical encoding and scaling improved model readiness  
- Feature analysis highlighted top predictors of churn  
## Business Metrics Impact
- Supports customer retention strategy  
- Enables targeted interventions for high-risk segments  
- Helps marketing prioritize engagement campaigns  
## Simple Story
Raw bank customer data is noisy but full of insights. After cleaning and analysis, the dataset now identifies churn patterns and prepares the data for predictive modeling, turning operational data into actionable business intelligence.
# Final Conclusions & Recommendations
## For Bank Management
- Focus retention efforts on high-risk customers identified by churn patterns  
- Incentivize inactive members to increase engagement  
- Target specific geographies or age groups with customized campaigns  
## For Data & Analytics Teams
- Continue monitoring and updating the dataset regularly  
- Apply machine learning models using cleaned, standardized data  
- Use visual dashboards to track churn trends in real time  
