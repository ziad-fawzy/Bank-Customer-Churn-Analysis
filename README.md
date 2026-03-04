# Bank Customer Churn Analysis

This project analyzes bank customer churn using Excel.  
It includes data cleaning, pivot tables, and a dashboard to visualize insights.

## Project Overview
The dataset contains information about bank customers, including:

- Geography
- Gender
- Age
- Balance
- Estimated Salary
- Number of Products
- Is Active Member
- Credit Card Ownership
- Exited (whether the customer left the bank)

The goal is to analyze customer churn and identify patterns in customer behavior.

## Steps Taken

1. *Data Cleaning:*  
   Used Power Query in Excel to clean and organize the raw data.

2. *Pivot Tables:*  
   Created pivot tables to analyze:
   - Number of customers who left vs stayed
   - Churn by country
   - Churn by gender
   - Churn by number of products
   - Churn by activity status

3. *Dashboard & Charts:*  
   Designed a dashboard with:
   - KPIs (Total Customers, Churn Rate %)
   - Pie chart for overall churn distribution
   - Column chart for churn by country
   - Column chart for churn by number of products
   - Bar chart for churn by active membership

## Insights

- Total customers: =COUNTA(CustomerID)  
- Churn rate: =COUNTIF(Exited,1)/COUNTA(CustomerID)  
- Countries with highest churn  
- Gender distribution in churn  
- Impact of number of products and activity status on churn

## Tools Used

- *Microsoft Excel* (Power Query, Pivot Tables, Charts)
