# Exploratory-Data-Analysis-and-Advance-data-analysis-

This project showcases a complete workflow for Exploratory Data Analysis (EDA) and Advanced SQL analytics using Microsoft SQL Server. It includes database creation, schema setup, exploratory queries, cumulative insights, ranking logic, part-to-whole analysis, performance analysis, and advanced business reporting such as Customer and Product reports. The objective is to demonstrate strong SQL proficiency, analytical thinking, and the ability to extract business-ready insights from raw transactional data.

Tech Stack

Microsoft SQL Server

T-SQL Querying

Window Functions (RANK, ROW_NUMBER, PARTITION BY)

Time-based and cumulative analytics

Business reporting logic

Project Structure
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

Exploratory Data Analysis (EDA)

The EDA section contains SQL scripts designed to understand the structure, behavior, and patterns within the dataset.

Database Exploration:
Analyzes tables, schemas, keys, data types, row counts, and detects data quality issues such as missing values or duplicates.

Dimension Exploration:
Focuses on categorical fields such as products, customers, categories, locations, and looks at relationships between entities.

Measures Exploration:
Examines numeric metrics, distribution ranges, min/max values, averages, and detects unusual variations.

Date Exploration:
Looks at ordering patterns across days, months, and years, identifying seasonality and time-based insights.

Change Over Time Analysis:
Tracks how key metrics evolve across time periods, highlighting trends and comparisons over months or years.

Magnitude Analysis:
Quantifies which customers, products, or regions contribute most to revenue or volume.

Cumulative Analysis:
Uses window functions to calculate running totals, cumulative revenue, month-to-date and year-to-date metrics.

Ranking Analysis:
Ranks customers, products, or categories to identify top performers, bottom performers, and outliers.

Advanced SQL Analysis

This section contains advanced SQL scripts designed to build business-ready analytical reports.

Customer Report

This report consolidates key customer metrics and behaviors.

Highlights:

Extracts essential fields such as customer names, ages, and transaction history.

Segments customers into VIP, Regular, and New categories.

Groups customers into age ranges.

Aggregates customer-level metrics including total orders, total sales, total quantity purchased, total products bought, and customer lifespan.

Computes KPIs such as recency, average order value (AOV), and average monthly spend.

Product Report

This analysis provides a full breakdown of product-level performance.

Highlights:

Retrieves product details including product name, category, subcategory, and cost.

Segments products into High-performing, Mid-range, and Low-performing groups.

Aggregates product-level metrics such as total orders, total sales, total quantity sold, total customers (unique), and product lifespan in months.

Calculates KPIs including recency, average order revenue (AOR), and average monthly revenue.

Part-to-Whole Analysis

Evaluates contribution percentages of categories, customers, or products toward overall metrics. Useful for identifying key drivers of sales or revenue concentration.

Performance Analysis

Analyzes category- or group-level performance trends, highlighting strong areas, weaknesses, and opportunities for improvement using ranking, aggregation, and comparative logic.

How to Run

Clone the repository.

Run the “Create Database and Schemas” script to initialize your database.

Load your dataset.

Run the EDA scripts in any order based on what you want to investigate.

Run the Advanced analysis scripts to generate business reports.

Export results or use them later to build dashboards.

Future Improvements

Add Power BI dashboards.

Add Python EDA notebooks using Pandas.

Add correlation and statistical analysis.

Create stored procedures for automated reporting.

Implement CTE-based models for analytics engineering workflows.

Why This Project Matters

This project demonstrates the ability to structure SQL queries effectively, investigate datasets thoroughly, apply analytical thinking, build cumulative and ranking logic, and produce business-ready insights using MS SQL Server. It highlights both foundational EDA skills and advanced SQL analysis suitable for real-world analytics and BI environments
