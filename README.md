# Bank Customer Churn Prediction Project

## Project Overview
The primary objective of the Bank Customer Churn Prediction project is to analyze the demographics and financial information of bank customers to predict whether they are likely to leave the bank (churn) or remain. Customer churn can have a significant impact on a bank's revenue and profitability, making it critical to identify at-risk customers in advance. This project leverages machine learning models to predict customer churn, allowing the bank to take proactive measures to retain high-value customers and improve customer satisfaction.

## About the Dataset
The dataset for this project is sourced from Kaggle and consists of 10,000 rows and 14 columns. Each row represents a bank customer, and the goal is to predict whether a customer will churn based on their demographic and financial data.

### Key Features:
- **Independent Variables (Predictors):**
  - Demographics: Age, Gender, Geography (Country)
  - Financial Data: Credit Score, Bank Balance, Estimated Salary
  - Bank-related Information: Number of Products used (NumOfProducts), Tenure (years with the bank), Active Member Status (IsActiveMember), and whether the customer holds a Credit Card (HasCrCard)
  
- **Target Variable:**
  - **Exited**: Binary flag indicating if the customer has left the bank (1 = churned, 0 = retained)

### Data Dictionary:
| Column Name       | Description                                                                           |
|-------------------|---------------------------------------------------------------------------------------|
| RowNumber         | Sequential number identifying the row in the dataset                                   |
| CustomerId        | Unique ID for each customer                                                           |
| Surname           | Customer’s last name                                                                  |
| CreditScore       | Credit score of the customer                                                          |
| Geography         | Country of the customer                                                               |
| Age               | Age of the customer                                                                   |
| Tenure            | Number of years the customer has been with the bank                                    |
| Balance           | Bank balance of the customer                                                          |
| NumOfProducts     | Number of products the customer is using at the bank                                   |
| HasCrCard         | Binary flag indicating if the customer holds a credit card with the bank (1 = yes, 0 = no) |
| IsActiveMember    | Binary flag indicating if the customer is an active member of the bank (1 = yes, 0 = no) |
| EstimatedSalary   | Estimated annual salary of the customer (in USD)                                       |
| Exited            | Binary flag indicating if the customer churned (1 = churned, 0 = retained)             |

## Objective and Approach
The objective is to build a predictive model that can accurately identify customers likely to churn. The project involves:
- **Data Preprocessing:** Cleaning the dataset and handling missing or inconsistent data.
- **Exploratory Data Analysis (EDA):** Investigating relationships between customer attributes and churn rates to identify key factors influencing churn.
- **Feature Engineering:** Creating new features or refining existing ones to improve model performance.
- **Model Building:** Using machine learning techniques such as Logistic Regression, Decision Trees, Random Forests, or Gradient Boosting to build and evaluate a predictive model.
- **Evaluation Metrics:** Measuring model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

By leveraging this dataset and applying appropriate machine learning techniques, the goal is to develop a churn prediction model that helps the bank retain customers and boost long-term profitability.

## Conclusion
With an accurate customer churn prediction model, the bank can identify customers at risk of leaving and implement targeted retention strategies. The insights gained from this analysis can contribute to increased customer loyalty and enhanced business performance.

