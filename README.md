# SALES and PROFITABILITY ANALYSIS: Identifying key revenue and profit driver

### 🌐 Portfolio   🔗 Read Article

# Over view

## Problem Statement 
The company has experienced growth across its products and regions but lacks visibility into the key factors driving revenue and profitability. Management wants to understand how product performance, customer behavior, and regional trends influence business outcomes.

## Objective
To analyze sales performance, product profitability, customer purchasing behavior, and regional trends in order to identify key revenue drivers, high-performing products, profitable customer segments, and opportunities to improve overall business performance.


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

[Data Collection]
      ↓
[Data Cleaning & Transformation]
      ↓
[Data Modeling]
      ↓
[Analysis]
      ↓
[Dashboard Development]
      ↓
[Reporting]

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

# Key Insights
1. Executive Summary
2. Product Profitability
3. Customer Behavior

# Recommendations


# Author
Lamidi Khadijat - Data Analyst
- 🔗 Connect with me on LinkedIn
- View my Portfolio 




