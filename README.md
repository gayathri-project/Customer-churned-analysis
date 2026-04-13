Project Overview

This project analyzes telecom customer data to understand factors influencing customer churn. The goal is to identify patterns in customer behavior and build a machine learning model that predicts whether a customer is likely to churn.

Customer churn is an important business problem because retaining existing customers is often more cost-effective than acquiring new ones. By analyzing customer attributes such as contract type, tenure, and monthly charges, this project provides insights that can help companies improve customer retention strategies.

Dataset

The dataset used in this project contains 7043 customer records and multiple features describing customer demographics, services, and billing information.

Important features include:

Gender

Contract Type

Tenure Months

Monthly Charges

Total Charges

Internet Service

Payment Method

Churn Label (target variable)

Tools and Technologies

This project was developed using the following tools:

Programming Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Machine Learning: Scikit-learn Algorithm used: Logistic Regression

Visualization Dashboard: Tableau Public

Development Environment: JupyterLab

Project Workflow

The project was completed in several stages:

Data Collection Loaded telecom churn dataset and explored dataset structure.

Data Cleaning

Handled missing values

Converted incorrect data types

Removed irrelevant columns

Exploratory Data Analysis (EDA) Visualized churn patterns based on contract type, gender, tenure, and monthly charges.

Feature Preparation Converted categorical variables using one-hot encoding.

Machine Learning Model Built a Logistic Regression model to predict customer churn.

Model Evaluation The model achieved approximately 80% accuracy in predicting customer churn.

Key Insights

Some important insights discovered during analysis:

Customers with month-to-month contracts have the highest churn rate.

Customers with higher monthly charges tend to churn more frequently.

Customers with longer tenure are less likely to churn.

Future Improvements

Possible improvements for this project include:

Testing additional machine learning models such as Random Forest or Gradient Boosting.

Performing hyperparameter tuning to improve model performance.

Adding interactive dashboards for deeper business insights.

Author

Gayathri Aspiring Data Analyst | Python | Machine Learning | Tableau
