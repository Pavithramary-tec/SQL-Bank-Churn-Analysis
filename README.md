# Bank Customer Churn Analysis (SQL)

## Overview
This project analyzes a bank customer dataset (10,000 records) using SQL to identify 
key factors driving customer churn. The goal was to answer real business questions 
using queries ranging from basic aggregation to window functions.

## Dataset
- **Source:** Bank Customer Churn dataset (Churn_Modelling.csv)
- **Rows:** ~10,000 customers
- **Columns:** CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, 
  Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited (churn flag)

## Tool Used
DB Browser for SQLite

## Questions Answered
1. What is the overall churn rate?
2. Which country (Geography) has the highest churn rate?
3. How do average balance and salary differ between churned and retained customers?
4. Which high-balance customers are most at risk of leaving?
5. How do customers rank by salary within their own country?
6. Does age group affect churn likelihood?
7. Are inactive members more likely to churn than active ones?

## Key Findings
- Overall churn rate: **[X]%**
- Highest churn rate by geography: **[Country] at X%**
- Churn rate by age group: **[Age group] showed the highest churn at X%**
- Inactive members churned at **[X]%** vs active members at **[X]%**

## Files
- `bank_churn_sql_analysis.sql` — all queries used in this analysis
- Screenshots of key query results included in this repo

## Skills Demonstrated
GROUP BY & aggregation, subqueries, window functions (RANK), CASE statements, 
business-question-driven SQL analysis
