# Project Telco Customer Churning Analysis

Project Idea:

- Predict customer churn using classification techniques like logistic regression or random forests.
- Perform feature engineering to understand which customer attributes (e.g., contract length, payment method) influence churn the most.

---
## About the Dataset

The telecoms churn dataset contains information aboutcustomers of a telecom company and whether they churned (cancelled their service) or not. It includes various features such as scustomer ddemographics (age, gender, etc.) andservice usage data (number of calles, minutes, billing methods, etc.)


This dataset consist of 7043 examples of 33 features, and is commonly used in machine learning and data analysis as a benchmark for predicting customer churn. It can be used to develop models that can identify at-risk customersand take steps to prevent churn, potentially leading to increased customer retention and revenue for the company.


### About the Feature

---
* **customerID**: Customer ID
* **gender**: Whether the customer is a male or female
* **Senior Citizen**: Whether the customer is a senior citizen or not (1,0)
* **Partner**: Whether the customer has a partner or not (Yes, No)
* **Dependents**: Whether the customer has a dependents or not (Yes, No)
* **Tenure Months**: Number of months the customer has stayed with the company
* **Phonse Service**: Whether the customer has a Phonse Service or not (Yes, No)
* **Multiple Lines**: Whether the customer has multiple lines or not (Yes, No, No phone service)
* **Internet Service**: Customer's internet service provider (DSL, Fiber optic, No)
* **Online Security**: Whether the customerhas online security or not (Yes, No, No internet service)
* **Online Backup**: Whether the customer has online backup (Yes, No, No internet service)
* **Device Protection**: Whether the customer has device protection or not (Yes, No, No internet service)
* **Tech Support**: Whether the customer has tech support or not (Yes, No, No internet service)
* **Streaming TV**: Whether the customer has streaming TV or not (Yes, No, No internet service)
* **Streaming Movies**: Whether the customer has streaming movies or not (Yes, No, No internet service)
* **Contract**: The contract term of the customer (Month-to-month, One year, Two year)
* **Paperless Billing**: Whether the customer has paperless or not (Yes, No)
* **Payment Method**: The customer's payment method (Electronic check, Mailed check, Bank Transfer (automatic), Credit card (automatic))
* **Monthly Charges**: The amount charged to the customer monthly
* **Total Charges**: The total amount charged to the customer
* **Churn Label**: Whether the customer churned or not (Yes, No)


### Initial Plan for Data Exploration

1. Data Overview
    * Load the dataset and review its structure
    * Identify key columns, including customer demographics and churn status

2. Descriptive Analysis
    * Obtain summary statistics for numeric columns
    * Visualize the churn distribution and identify trends

3. Categorical Analysis
    * Explore categorical variables
    * Analyze their impact on churn rates

4. Churn Reasons
    * Investigate reasons for churn
    * Understand the main drivers of customer attrition

5. Correlation Analysis

6. Hypotheis Testing
    * Hypothesis 1: Phone Service Impact Churn
    * Hypothesis 2: Contract Type Affects Churn
    * Hypothesis 3: Seniority Affects Churn

7. Suggests for the next steps in analyzing the data

8. Summary of quality of data



## Suggestions for the next steps in analyzing the data
---
* **Customer Segmentation:** 

    We can explore the customer segmentation to better understand different customer groups.
* **Principal Component Analysis:**

    We can apply PCA to reduce the dimensionality of the data and focus on more important features.

* **Machine Learning Modeling:**

    Applying machine learning techniques to build predictive models for customer churn. We can use classification algorithms like logistic regression, decision tress, or gradient boosting to predict which customers are likely to churn.
