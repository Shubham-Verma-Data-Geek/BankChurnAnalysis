Project Overview:

This project provides a comprehensive analysis of bank churn data, where churn refers to customers who have left the bank, also known as attrition. The dataset used is a sample intended for practice in report creation and data analysis using PowerBI.

Objectives:

Identify and understand the factors contributing to customer churn.
Develop actionable insights to help reduce churn rates.

Workflow:
1. Data Connection - Establish a stable connection to the bank churn data source.
2. Data Preparation - Data cleaning and preparation are critical for accurate analysis. The steps include:

Initial Setup:

Check data types and column names.
Remove the 'Estimated Salary' column.
Ensure column names start with a capital letter.

Rename columns to:

Credit Score
Credit Card Status
Activity Status
Churn Status
Add an example column for products (e.g., Prod 1).

Value Modification:

Modify values for clarity:
Churn Status: 1 for Churned, 0 for Not Churned
Activity Status: 1 for Active, 0 for Inactive
Credit Card Status: 1 for Owned, 0 for Not Owned

Conditional Columns:

Create columns based on existing data:
Age Group (from Age)
Credit Scores (from Credit Score)
Account Balance (from Balance)

3. Data Modeling and Analysis

Reference Tables and Conditional Columns:

Create a reference table from the customer data table, rename it 'Age Groups', keep only the 'Age Group' column, and remove duplicates.
Add an 'Age Group ID' conditional column in the 'Age Groups' table.
Similarly, create reference tables for 'Account Balance' and 'Credit Scores' and add respective IDs as conditional columns.

4. Creating Measures

Develop measures to aid in the analysis:


Calculate the number of customers.
Calculate the number of lost customers.
Calculate the churn rate.

5. Data Visualization

Visual representation of data provides intuitive insights. The report will include:

Cards:

Displaying the number of customers.
Representing number of active and inactive customers
Showcasing the churn rate.
Representing the number of lost customers.


Charts:

Donut charts for:

Number of customers by gender.
Number of customers by activity status.
Number of customers by credit card status.
Number of customers by country.
Line clustered bar chart showing customers and churn rate by age group .
Line and stacked column chart for customers and churn rate by credit score.
Line chart depicting customer losses by country.
Stacked column chart representing customers by Customer group.
This structured approach ensures a thorough analysis of the bank churn data, leading to actionable insights for reducing customer attrition.





