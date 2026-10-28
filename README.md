# Customer Churn Analysis - 64374 Users

## Business Problem
Telecom company is losing customers. Analyzed 64374 customers to understand churn reasons and how to retain them. Currently only 2317 customers are safe (3.6%).

## Data Overview
Total Customers: 64374
Data Sources: Excel, SQL, Python, Power BI

Customer Segmentation:
- High Spending Customers: 20809 | Avg Spend 849.78 | At Risk 19991 | Safe 818
- Medium Spending Customers: 21148 | Avg Spend 546.83 | At Risk 20399 | Safe 749  
- Low Spending Customers: 22417 | Avg Spend 248.92 | At Risk 21667 | Safe 750

## Key Insights

1. Subscription:
Basic Plan churn 48.28% vs Premium 46.50%. Premium customers are more loyal.

2. Support Calls:
0-3 support calls = 24% churn
5+ support calls = 60% churn
Support experience is the main reason for churn.

3. Payment Delay:
0-14 days delay = 10% churn
15-19 days delay = 51% churn
25-30 days delay = 76% churn
Need strict follow up after 14 days.

## Scenario Analysis
Current Safe: 3.60% (2317)
Best Case: 23.30% (15000) - if support issues fixed
Worst Case: 1.55% (1000)

If we fix support and payment, we can save 15000 customers.

## Model
Random Forest Classifier
Accuracy: 89.35%
Used for predicting at-risk customers.

## Project Structure
excel - Data cleaning and business metrics
sql - Queries for churn analysis  
python - EDA and ML model
powerbi - Dashboard with RLS

## Tools
Excel, MySQL, Python (Pandas, Sklearn, Matplotlib), Power BI

Mudit Kulshrestha - Data Analyst
