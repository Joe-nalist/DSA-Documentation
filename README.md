#  DSA-Documentation
# Data Analysis Project: Insights from DSA-Documentation

## 📊 Project Overview

This project demonstrates a full data analysis pipeline using **Microsoft Excel**, **SQL Server**, and **Power BI**. The goal was to collect, clean, analyze, and visualize data to derive meaningful insights that can support decision-making processes.

## 🛠️ Tools & Technologies

- **Microsoft Excel** – Data cleaning, preliminary analysis, pivot tables
- **SQL Server** – Data storage, complex queries, joins, aggregations
- **Power BI** – Interactive data visualizations and dashboards

## 📁 Dataset

The dataset contains information on [e.g., sales records, customer data, transactions, employee performance, etc.], covering a time period from [start date] to [end date]. It was sourced from [mention source, e.g., internal business records, Kaggle, or mock data].

## 🧹 Data Preparation

- Cleaned raw data in Excel by removing duplicates, handling missing values, and standardizing formats.
- Uploaded cleaned data to **SQL Server** for efficient querying and structured storage.
- Normalized tables and defined primary/foreign key relationships where applicable.

## 🧾 SQL Analysis

Key queries performed include:
- Aggregating data to identify trends over time
- Joining multiple tables to enrich analysis
- Filtering by key performance indicators (KPIs)

Example SQL Query:
```sql 
SELECT Region, SUM(Sales) AS TotalSales
FROM SalesData
GROUP BY Region
ORDER BY TotalSales DESC;
