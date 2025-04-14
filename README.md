# 📊 Sales Insights Dashboard – SQL + Power BI

Welcome to my end-to-end data analysis project for **AtliQ Hardware**, where I’ve designed a full-stack sales insights dashboard using **MySQL** for data extraction and **Power BI** for transformation, modeling, and storytelling.

---

## 🧠 Project Objective

To help the sales leadership at AtliQ Hardware uncover hidden patterns in sales data, improve decision-making, and reduce manual reporting time through a dynamic, automated Power BI dashboard.

---

## 🛠 Tools & Technologies

- **SQL (MySQL):** Data discovery, joins, filtering, aggregations
- **Power BI:**
  - Data modeling with star schema
  - Power Query for ETL
  - DAX for KPIs and business logic
- **Power BI Service (Optional):** For sharing dashboards

---

## 🔄 Process Overview

### 1. Data Discovery (MySQL)
- Connected to a transactional sales database
- Wrote SQL queries to explore and validate data
- Joined multiple tables (`transactions`, `products`, `markets`, `customers`, `date`)

### 2. ETL & Data Cleaning (Power Query)
- Removed nulls and duplicate rows
- Normalized currency fields
- Ensured correct data types (Date, Decimal, Text)
- Created calculated columns (Year-Month, Product Type Mapping)

### 3. Data Modeling
- Built a **Star Schema** with clear relationships
  - Fact Table: `transactions`
  - Dimension Tables: `customers`, `products`, `markets`, `date`

### 4. Dashboard Design (Power BI)
- KPIs: Total Revenue, Sales Quantity, Profit Margin
- Profit margin target comparison using slicers & DAX
- Market-wise and customer-wise performance breakdown
- Trendline analysis of revenue and profit over time
- Conditional flagging for underperformance

---

## 📸 Dashboard Snapshots

> ![Dashboard Screenshot](./screenshots/overview.png)
> ![Profit Analysis](./screenshots/profit_insights.png)

---

## 📈 Key Insights

- Delhi NCR contributed over **50% of total revenue**, yet had **low profit margins**
- Bhubaneshwar, although smaller in revenue, achieved **10.5% profit margin**
- **Brick & Mortar** customers account for nearly **80%** of revenue
- The dynamic profit margin target allowed identification of markets falling short

---

## 🎯 Skills Demonstrated

- SQL querying & data profiling
- Data modeling and ETL
- Power BI dashboard development
- DAX for calculated measures and business KPIs
- Insight storytelling for business decisions

---

## 💼 Role Alignment

This project aligns well with roles such as:
- Business Analyst
- Data Analyst
- Supply Chain Analyst
- Operations Analyst

---

## 📂 Files Included
