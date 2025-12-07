#📊 Exploratory Data Analysis & Advanced SQL Data Analysis

This project showcases a complete workflow for Exploratory Data Analysis (EDA) and Advanced SQL analytics using Microsoft SQL Server. It includes database creation, schema setup, exploratory queries, cumulative insights, ranking logic, part-to-whole analysis, performance analysis, and advanced business reporting such as Customer and Product reports.
The goal is to demonstrate strong SQL proficiency, analytical thinking, and the ability to turn raw transactional data into business-ready insights.

🛠️ Tech Stack

Microsoft SQL Server

T-SQL Querying

Window Functions (RANK, ROW_NUMBER, PARTITION BY)

Time-based & cumulative analytics

Business reporting logic

📁 Project Structure
Exploratory-Data-Analysis-and-Advance-data-analysis/
│
├── EDA/
│   ├── Change over time analysis
│   ├── Create Database and Schemas
│   ├── Cumulative analysis
│   ├── Database Exploration
│   ├── Date Exploration
│   ├── Dimension Exploration
│   ├── Magnitude analysis
│   ├── Measures Exploration
│   └── Ranking analysis
│
└── Advanced analysis/
    ├── Customer report
    ├── Part to whole analysis
    ├── Performance analysis
    └── Product Report

🔍 Exploratory Data Analysis (EDA)

The EDA section contains SQL scripts designed to understand the structure, patterns, and behavior of the dataset.

🧱 Database Exploration

Examines schemas, tables, primary keys, foreign keys, data types

Checks row counts & data quality (nulls, duplicates, outliers)

🏷️ Dimension Exploration

Analyzes categorical fields (products, customers, categories, locations)

Understands hierarchical relationships

📏 Measures Exploration

Examines numeric fields

Evaluates min, max, mean, distribution & unusual patterns

📆 Date Exploration

Identifies trends across days, months, years

Detects seasonality & recurring patterns

📈 Change Over Time Analysis

Tracks how key metrics evolve

Compares month-to-month or year-to-year performance

⚖️ Magnitude Analysis

Identifies high-impact entities

Ranks contribution to revenue, quantity, etc.

➕ Cumulative Analysis

Running totals

MTD, YTD, rolling revenue

Window function-based insights

🏅 Ranking Analysis

Uses RANK(), DENSE_RANK(), ROW_NUMBER()

Finds top/bottom performers

Identifies outliers & priority targets

⚡ Advanced SQL Analysis

These scripts turn data into business-level reports suitable for BI dashboards and decision-making.

👤 Customer Report

A complete breakdown of customer behavior and value.

✨ Highlights

Pulls essential customer attributes (name, age, transactions)

Segments customers into VIP, Regular, New

Groups customers by age

Customer-level metrics:

Total orders

Total sales

Total quantity purchased

Total products bought

Customer lifespan

KPIs:

Recency

Average Order Value (AOV)

Average Monthly Spend

📦 Product Report

Detailed analysis of product performance.

✨ Highlights

Retrieves name, category, subcategory, cost

Segments products into High-performing, Mid-range, Low-performing

Product-level metrics:

Total orders

Total sales

Total quantity sold

Unique customer count

Product lifespan in months

KPIs:

Recency

Average Order Revenue (AOR)

Average Monthly Revenue

🥧 Part-to-Whole Analysis

Evaluates contribution of categories, customers, or products

Helps identify the biggest drivers of revenue and sales

Useful for prioritization & resource allocation

📊 Performance Analysis

Compares performance across groups, categories, or time periods

Uses ranking & aggregations

Identifies strong areas, weak areas, and growth opportunities

🚀 How to Run

Clone the repository

Run the Create Database and Schemas script

Load your dataset

Run EDA scripts in any order

Run Advanced analysis scripts for business insights

Use results for dashboards (Power BI coming soon)

🔮 Future Improvements

Power BI dashboards

Python EDA (Pandas)

Correlation & statistical analysis

Automated stored procedures

Analytics-engineering-style CTE models

⭐ Why This Project Matters

This project demonstrates the ability to:

Structure SQL analyses professionally

Investigate datasets deeply

Build advanced analytical logic

Calculate complex KPIs

Deliver insights directly from SQL

Combine EDA + advanced business reporting in one structured project
