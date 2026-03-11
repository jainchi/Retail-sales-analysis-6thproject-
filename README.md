# Retail-sales-analysis-6thproject-


# 🛒 Retail Sales SQL Data Analysis Project

## 📌 Project Overview

This project analyzes **retail sales data using SQL** to uncover business insights such as customer behavior, sales trends, and product performance.

The dataset contains transaction-level data including customer demographics, product categories, and sales values. SQL queries are used to perform **data cleaning, exploration, and business analysis**.

---

## 🗂 Dataset Information

Table: `retail_sales`

| Column          | Description                   |
| --------------- | ----------------------------- |
| transactions_id | Unique transaction identifier |
| sale_date       | Date of the sale              |
| sale_time       | Time of transaction           |
| customer_id     | Unique customer ID            |
| gender          | Customer gender               |
| age             | Customer age                  |
| category        | Product category              |
| quantity        | Number of products purchased  |
| price_per_unit  | Price per unit                |
| cogs            | Cost of goods sold            |
| total_sale      | Total transaction value       |

---

## 🧹 Data Cleaning

The dataset was checked for:

* Missing values
* Null records
* Data consistency

Example SQL used:

```sql
SELECT *
FROM retail_sales
WHERE quantity IS NULL
OR price_per_unit IS NULL
OR total_sale IS NULL;
```

---

## 📊 Data Analysis & Business Questions

The following business questions were answered using SQL:

1️⃣ What are the **total sales by product category**?

2️⃣ Which **customers generate the highest revenue**?

3️⃣ What are the **top selling months each year**?

4️⃣ How do **sales vary by gender**?

5️⃣ What transactions generated **sales above 1000**?

6️⃣ How many **unique customers purchase from each category**?

7️⃣ Which **time of day generates the most sales**?

---

## 🧠 SQL Skills Demonstrated

* Data Cleaning
* Aggregate Functions
* GROUP BY
* HAVING
* Window Functions
* Subqueries
* Common Table Expressi
