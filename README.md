# Telecom Customer Churn Dataset

## Overview

This dataset comprises information about telecom company customers and their churn status (whether they canceled their service). It includes a variety of features such as customer demographics (age, gender, etc.) and service usage data (number of calls, minutes, billing method, etc.). The dataset contains 7043 records and 21 attributes, making it a widely used benchmark for predicting customer churn in machine learning and data analysis. It can be used to develop models to identify at-risk customers, aiding in customer retention and increasing company revenue.

For additional details, refer to the following resources:
- [Kaggle](https://www.kaggle.com)
- [UCL](https://www.ucl.ac.uk)

## Dataset Features

- **customerID:** Unique identifier for each customer
- **gender:** Customer's gender (Male, Female)
- **Senior Citizen:** Indicates if the customer is a senior citizen (1 for Yes, 0 for No)
- **Partner:** Indicates if the customer has a partner (Yes, No)
- **Dependents:** Indicates if the customer has dependents (Yes, No)
- **tenure:** Number of months the customer has been with the company
- **Phone Service:** Indicates if the customer has phone service (Yes, No)
- **Multiple Lines:** Indicates if the customer has multiple lines (Yes, No, No phone service)
- **Internet Service:** Type of internet service the customer has (DSL, Fiber optic, No)
- **Online Security:** Indicates if the customer has online security (Yes, No, No internet service)
- **Online Backup:** Indicates if the customer has online backup (Yes, No, No internet service)
- **Device Protection:** Indicates if the customer has device protection (Yes, No, No internet service)
- **Tech Support:** Indicates if the customer has tech support (Yes, No, No internet service)
- **Streaming TV:** Indicates if the customer has streaming TV service (Yes, No, No internet service)
- **Streaming Movies:** Indicates if the customer has streaming movies service (Yes, No, No internet service)
- **Contract:** The length of the customer's contract (Month-to-month, One year, Two year)
- **Paperless Billing:** Indicates if the customer has paperless billing (Yes, No)
- **Payment Method:** The customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **Monthly Charges:** Monthly amount charged to the customer
- **Total Charges:** Total amount charged to the customer
- **Churn Label:** Indicates if the customer churned (Yes, No)

## Initial Plan for Data Exploration

### 1. EDA
- Load the dataset and examine its structure.
- Identify key columns, including those related to customer demographics and churn status.

### 2. Descriptive Analysis
- Calculate summary statistics for numeric columns.
- Visualize churn distribution and identify trends.

### 3.Correlation Analysis
- Investigate correlations between different variables.

### 4.Univariate Analysis
- Statistical Normality Tests

### 5.Outliers Analysis
- identifying and handling data points that deviate significantly from the rest of the dataset.

### 6. Hypothesis Testing
- Test the following hypotheses:
  - **Hypothesis 1:** Phone service impacts churn.
  - **Hypothesis 2:** Contract type affects churn.
  - **Hypothesis 3:** Seniority affects churn.


### 7.Machine Learning Model Evaluations and Predictions
- train three models (KNeighborsClassifier, LogisticRegression, and XGBoost) and then ensemble them to improve the performance.

