Olist E-Commerce Sales & Strategy Dashboard
📊 Project Overview
This project provides a comprehensive analysis of the Olist E-commerce dataset (Brazil). The goal was to transform raw data into actionable business insights using Excel Power Pivot and Data Modeling. The dashboard tracks key performance indicators (KPIs), sales trends, and customer behavior to help stakeholders make data-driven decisions.
🛠️ Tech Stack
Microsoft Excel: Main platform for analysis.
Power Query: Data cleaning, handling missing values, and feature engineering (e.g., calculating Response Lag).
Power Pivot (DAX): Building a relational data model and creating complex measures.
Data Visualization: Interactive dashboard with dynamic charts and slicers.
📂 Data Architecture (Star Schema)
I designed a robust Star Schema to connect multiple tables, ensuring efficient data filtering and accurate calculations.
Fact Table: Order_Items (containing price, freight, and product IDs).
Dimension Tables: Customers, Products, Sellers, Orders, Payments, and Reviews.
Relationships: Established 1:N (One-to-Many) relationships to allow seamless cross-table analysis.
🧼 Key Data Cleaning Steps
Response Time Analysis: Created a Response_lag column to measure the time between customer reviews and company answers.
Error Handling: Cleaned negative durations and inconsistent date formats.
Localization: Integrated a translation table to convert product categories from Portuguese to English.
📈 Key Insights & KPIs
Total Revenue: Over $12.4M in total sales.
Average Order Value (AOV): Approximately $126 per order.
Top Performance: "Health & Beauty" and "Watches & Gifts" emerged as the highest-grossing categories.
Geographical Trends: São Paulo (SP) represents the largest customer base by a significant margin.
🖥️ Dashboard Features
Executive Summary: High-level KPIs for quick business health checks.
Sales by Quarter: Visualizing growth patterns from 2016 to 2018.
Payment Preferences: Analysis of credit card vs. boleto/voucher usage.
Top 10 Rankings: Dynamic bar charts for States and Product Categories.
