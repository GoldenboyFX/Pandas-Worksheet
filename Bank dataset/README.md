# Bank Customer Churn Analysis

## Project Overview
Analysis of a bank's customer dataset to understand churn patterns and identify key drivers of customer attrition.

**Dataset**: 10,000 customers with demographic and account behavior information.

**Goal**: Identify why customers leave the bank and provide actionable business recommendations.

## Key Insights

- Overall Churn Rate: **20.37%** (2,037 customers left)
- **Germany** has significantly higher churn (**32.44%**) compared to France (16.15%) and Spain (16.67%)
- Churners are **older** on average (44.8 vs 37.4 years)
- Customers with **3 or 4 products** have very high churn rates
- **Active Membership** is one of the strongest predictors — inactive customers churn much more
- Females churn at a higher rate than males (25.1% vs 16.5%)

## Customer Segments
- **High Risk**: German customers, Older customers with high balances, Customers with 3+ products
- **Lower Risk**: Active members, Customers with 1-2 products

## Technologies Used
- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

## Visualizations

![Overall Churn Distribution](Bank%20dataset/Bank%20data%20images/Churn_Distribution.png)
![Age Distribution](images/Age_distribution_by_churn.png)
![Balance Distribution](Bank%20dataset/Bank%20data%20images/Balance_distribution_by_churn.png)


## Business Recommendations
1. Launch targeted retention campaigns for **German customers**
2. Focus on converting customers into **Active Members**
3. Investigate product strategy for customers with 3+ products
4. Offer special loyalty programs for older high-balance customers



