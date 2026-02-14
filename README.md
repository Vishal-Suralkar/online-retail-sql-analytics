# 📊 Online Retail SQL Analytics Project

##  Project Overview

This project analyzes 500k+ retail transactions using MySQL and Python to extract business insights related to revenue trends, customer behavior, and geographic performance.

The goal was to simulate a real-world business analytics scenario using structured SQL queries instead of relying solely on pandas.

---

## Tools & Technologies

- MySQL
- SQL (CTE, Window Functions, Aggregations)
- Python (Pandas, Matplotlib)
- Jupyter Notebook

---

## Data Cleaning Steps

- Removed cancelled invoices
- Filtered negative quantities
- Removed missing customer IDs
- Created TotalPrice column (Quantity × Price)
- Converted InvoiceDate to datetime

---

## 📈 Key Analysis Performed

### 1️⃣ KPI Overview
- Total Revenue
- Total Orders
- Total Customers

### 2️⃣ Time-Based Analysis
- Monthly Revenue Trend
- Monthly Orders Trend
- Seasonality Identification

### 3️⃣ Geographic Analysis
- Top 10 Countries by Revenue

### 4️⃣ Customer Analysis
- Top 10 High-Value Customers
- Customer Spending Distribution

### 5️⃣ Advanced SQL
- RFM (Recency, Frequency, Monetary) Analysis using CTE
- Customer Ranking using Window Function (RANK)

---

## Key Business Insights

- Revenue peaks in Q4, indicating strong seasonal demand.
- UK contributes the majority of total revenue.
- A small percentage of customers generate a large portion of revenue.
- Revenue trends align closely with order volume trends.
- High-value customers can be targeted for retention strategies.

---

## SQL Concepts Demonstrated

- GROUP BY & Aggregations
- DATE_FORMAT
- CTE (Common Table Expressions)
- Window Functions
- Indexing for Performance Optimization

---

## Dataset

Online Retail II dataset containing over 500,000 transaction records.

---

## Author

Vishal  
Aspiring Data Analyst | SQL | Python | Business Analytics
