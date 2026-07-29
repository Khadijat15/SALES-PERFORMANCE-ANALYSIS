# SALES and PROFITABILITY ANALYSIS: Identifying key revenue and profit driver

### 🌐 Portfolio   🔗 Read Article

# 🌼 Project Overview
A company operating across six countries and ten regions sells bikes, clothing, and accessories. While sales volume appeared to increase over time, revenue growth did not always rise at the same rate, making it difficult to identify the factors influencing business performance.
This project analyzes 30 months of transaction data to evaluate sales trends, product profitability, customer behavior, and regional performance. The analysis aims to determine whether gaps in revenue performance are linked to product mix, profitability, customer purchasing patterns, or market concentration.
The findings revealed a growing number of low-margin products within the portfolio, a heavy reliance on the bike category for revenue generation, and revenue concentration in a small number of key markets.


## Objective
1. Determine whether sales performance increased throughout the analysis period.
2. Identify the key products, categories, customers, and markets driving revenue and profitability.
3. Evaluate product profitability by identifying products that fall below the target margin and those that contribute most to overall profit.
4. Analyze customer and regional performance to understand their impact on business growth.
5. Provide data-driven recommendations to improve profitability and support business decision-making.

# 🧰 Tool
| Tool | Purpose|
|------|--------|
|Power Query| Claening and Transformation|
| Power BI| Data Modelling and Visualization|


# Dataset Description

The dataset was obtained from Kaggle. It follows a star schema with one fact tables and six dimension tables.
| Tables | Description | Rows |
|--------| ------------| -----|
| fact_sales | contains sales record across various territories | 56,046|
| Dim_customers | contains customers  details | 18,148 |
| Dim_products| Contains information about products offered by the business | 293 |
| Dim_product category | records of available product category | 4|
| Dim_Product subcategory | Information about various subcategory | 37|
| Dim_terriotry | Contains territory information | 10|
| Dim_date | Date covering Jan 1st 2015 to Dec 31st 2017 | 1096|

# Data Workflow

Data Collection
      ↓
Data Cleaning
      ↓
Data Modeling
      ↓
Data Analysis
      ↓
Dashboard Development
      ↓
Insights & Recommendations

1. Data Collection: The dataset was obtained from Kaggle.
2. Data Cleaning: Ensure data quality, Checked for duplicated records,  Replaced M with "Male" and F with "Female", and Promoted Headers
3. Data Transformation: Concatenate the first name and last name to get the full name, Added Price and cost column into the sales table, calculated the total price and total cost in order to obtain total profit and calculate profit Margin.
4. Data Modeling: Created relationships between tables and designed a star schema for reporting.
5. Data Analysis: Created DAX measures and explored sales, profitability, and customer trends.
6. Dashboard Development: Built a three page interactive Power BI dashboards to visualize key metrics.
7. Reporting: Documented key findings and provided actionable recommendations. 

# Data Model

# ✂️ Tool Used
- Power BI

# 📌 Key Insights
1. Executive Summary
2. Product Profitability
3. Customer Behavior

# 🌻 Recommendations


# Author
Lamidi Khadijat - Data Analyst
- 🔗 Connect with me on LinkedIn
- View my Portfolio 




