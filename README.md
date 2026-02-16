📊 Customer Behavior Analysis
📌 Overview

Customer_Behavior_Analysis is an end-to-end Data Analytics project that analyzes customer shopping behavior to uncover trends, patterns, and business insights.

This project simulates a real-world analytics workflow using:

Python for data cleaning & EDA

SQL (PostgreSQL/MySQL/SQL Server) for business analysis

Power BI for interactive dashboard development

Report & Presentation for data storytelling

The goal is to transform raw customer shopping data into actionable insights for better business decision-making.

📂 Dataset

File: customer_shopping_behavior.csv
Records: 3,900 rows
Features: 18 columns

This dataset contains customer shopping and transaction data, including:

🔹 Customer Information

Customer ID

Age

Gender

Location

Subscription Status

Previous Purchases

🔹 Product Details

Item Purchased

Category

Size

Color

Season

🔹 Transaction Details

Purchase Amount (USD)

Payment Method

Shipping Type

Discount Applied

Promo Code Used

Frequency of Purchases

Review Rating

The dataset allows analysis of:

Revenue trends

Category performance

Customer segmentation

Payment behavior

Seasonal shopping patterns

Impact of discounts and subscriptions

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning & EDA

SQL – Business queries and KPI extraction

PostgreSQL / MySQL / SQL Server – Database management

Power BI – Dashboard & visualization

Gamma – Presentation creation

Jupyter Notebook – Development environment

🔎 Project Workflow
1️⃣ Data Loading (Python)

Imported CSV dataset using Pandas

Checked structure, data types, and missing values

2️⃣ Exploratory Data Analysis (EDA)

Summary statistics

Sales distribution analysis

Category-wise performance

Customer segmentation insights

Trend analysis

3️⃣ Data Cleaning

Handled missing/null values

Removed duplicates

Standardized column names

Converted data types

Treated outliers

4️⃣ SQL Analysis

File: customer_behavior_sql_queries.sql

Performed business-driven SQL analysis such as:

Total revenue calculation

Category-wise sales

Top spending customers

Average purchase value

Payment method analysis

Monthly/Yearly trends

GROUP BY & aggregate functions

Joins and subqueries

📊 Power BI Dashboard

File: customer_behavior.pbix

The dashboard includes:

📌 KPI Cards (Total Revenue, Avg Purchase, Total Customers)

📈 Sales Trend Over Time

📊 Category-wise Revenue

🌍 Customer Segmentation Insights

💳 Payment Method Distribution

🔎 Interactive Filters & Slicers

The dashboard enables decision-makers to quickly identify performance trends and customer behavior patterns.

📈 Key Insights

Identified top-performing product categories

Analyzed customer spending patterns

Detected seasonal sales trends

Evaluated preferred payment methods

Highlighted high-value customer segments

These insights can help businesses optimize marketing strategies and improve revenue performance.

📁 Repository Structure
Customer_Behavior_Analysis/
│
├── LICENSE
├── README.md
├── customer_shopping_behavior.csv
├── customer_behavior_sql_queries.sql
├── customer_behavior.pbix

▶️ How to Run
🔹 Python Analysis

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open Jupyter Notebook

Load the dataset:

import pandas as pd
df = pd.read_csv("customer_shopping_behavior.csv")

🔹 SQL Analysis

Import the dataset into PostgreSQL / MySQL / SQL Server

Open and execute:

customer_behavior_sql_queries.sql

🔹 Power BI Dashboard

Open customer_behavior.pbix

Refresh data connection (if needed)

🎯 Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

SQL Query Writing

KPI Development

Dashboard Design

Business Insight Generation

Data Storytelling

📌 Conclusion

This project demonstrates the complete lifecycle of a Data Analytics project — from raw data processing to delivering business insights through dashboards and reports.

It showcases strong analytical thinking, SQL proficiency, and business intelligence skills suitable for a Data Analyst role.
