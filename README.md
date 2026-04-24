# Retail-Analytics-Dashboard
End-to-end retail analytics project using Snowflake, SQL, and Power BI


**Project Overview**

This project analyzes retail sales data to understand performance across revenue, profit, customer segments, and operations. The focus is on building a complete pipeline from raw data in Snowflake to insights presented through a Power BI dashboard.

The goal is to replicate a real business reporting workflow where data is cleaned, transformed, and visualized for decision-making.

**Tools & Technologies**
Snowflake (data storage and warehousing)
SQL (data cleaning and analysis)
Power BI (dashboard development and visualization)

**Dataset**
Retail Superstore dataset
Contains order-level transaction data including sales, profit, discounts, region, category, customer segment, and shipping details

**Data Workflow**
Loaded raw dataset into Snowflake using staging
Created a structured raw table and imported data using COPY INTO
Cleaned and transformed data using SQL queries
Built KPI-focused and exploratory analysis queries
Connected Snowflake to Power BI
Developed an interactive dashboard using DAX measures and visuals

**Key Metrics (KPIs)**
Total Sales
Total Profit
Total Orders
Profit Margin

**Key Insights**

**Regional Performance**

West and East regions generate the highest sales
Central region consistently shows negative profitability, indicating operational inefficiencies

**Discount Impact**

Higher discounting in the Central region is closely linked to lower profit margins
Regions with more controlled discount strategies perform better overall

**Category Performance**

Technology is the strongest category in terms of revenue
Furniture underperforms in profitability despite steady sales volume

**Segment Analysis**

Consumer segment contributes the most to overall sales
Home Office segment delivers the highest profit margin

**Shipping Analysis**

Standard Class accounts for most shipping delays
Same Day shipping is the fastest option but used less frequently

**How to Use**

Download the .pbix file from the dashboard/ folder
Open it using Power BI Desktop
Use filters and visuals to explore insights interactively
