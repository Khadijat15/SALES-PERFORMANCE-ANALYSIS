# SALES and PROFITABILITY ANALYSIS: Identifying Key Drivers of Sales, Profitability and Growth

### 🌐 [Portfolio](https://www.linkedin.com/in/khadijatlamidi/)  🔗 [Read Article](https://medium.com/@omowunmikhadijat011/beyond-revenue-uncovering-the-key-drivers-of-sales-profitability-and-growth-2b920e1de289)

# 🌼 Project Overview
A company operating across six countries and ten regions sells bikes, clothing, and accessories. While sales volume appeared to increase over time, revenue growth did not always rise at the same rate, making it difficult to identify the factors influencing business performance.
This project analyzes 30 months of transaction data to evaluate sales trends, product profitability, customer behavior, and regional performance. The analysis aims to determine whether gaps in revenue performance are linked to product mix, profitability, customer purchasing patterns, or market concentration.
The findings revealed a growing number of low-margin products within the portfolio, a heavy reliance on the bike category for revenue generation, and revenue concentration in a small number of key markets.


# Objective
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
<img width="698" height="333" alt="Image" src="https://github.com/user-attachments/assets/f11ddb63-c48f-4dc8-a1dd-a4ccc4c72805" />


# 📌 Key Insights
1. Executive Summary
<img width="660" height="383" alt="Image" src="https://github.com/user-attachments/assets/ce709813-8d79-4963-8df2-1b8d2903d3fd" />

- Sales volume increased during the analysis period.
-  Bikes generated 95% of total revenue, indicating a high dependency on a single product category.
-  R evenue growth did not increase proportionally with sales volume, suggesting the influence of product mix, pricing, or margin pressures.

2.  Product Profitability
 <img width="554" height="337" alt="Image" src="https://github.com/user-attachments/assets/33ef3e90-4cd3-4ac5-97d6-7980bf6039ec" />
 
- The business maintained an average profit margin of approximately 42%.
- The number of products below the target margin increased over time.
-  High revenue products were not always the most profitable products.

   
3.  Customer Behavior
 <img width="608" height="380" alt="Image" src="https://github.com/user-attachments/assets/cd624c88-9206-4575-8907-210b16cc637f" />
 
- Customer purchasing power increased throughout the analysis period.
- Revenue was concentrated in a few key markets, particularly the United States.
-  Growth was primarily driven by existing high performing markets rather than expansion into new markets.

# 🌻 Recommendations

|Priority| Recommendation| Business Impact | Suggested Owner|
|--------|---------------|-----------------|----------------|
|High   | Review pricing and cost structure of high sales, low margin products| Improves profitability and margin performance | Product Manager/Finance Team|
|High   | Increase visibility and sales of non-bike categories to reduce revenue concentration | Diversifies revenue sources and reduces category risk| Marketing Team/Product Team|
|Medium | Expand marketing efforts in underperforming regions and countries | Support customer acquisition and revenue growth | Sales & Marketing Team|
|Medium| Monitor products falling below margin and asses their performance regularly | Prevents margin erosion and improves product portfolio management | Product Team/Finance Team|
| Low  | Develop performance dashboards for ongoing monitoring of sales and profitability metrics | Enables faster decision making and performance tracking | Business Intelligence Team |



# Author
Lamidi Khadijat - Data Analyst

# 🔗 Connect With Me
-  [LinkedIn](https://www.linkedin.com/in/khadijatlamidi/)
- [Portfolio](https://lamidikhadijat.vercel.app/)
- [Email](mailto:omowunmikhadijat011@gmail.com)




