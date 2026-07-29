# 🍕 Pizza Sales SQL Analysis

## 📌 Project Overview

This project analyzes a Pizza Sales dataset using MySQL to uncover key business insights. The analysis covers customer ordering patterns, sales performance, revenue generation, and product popularity using SQL queries ranging from basic to advanced concepts.

---

## 🎯 Objectives

- Analyze overall sales performance
- Calculate total revenue and total orders
- Identify the highest-priced pizza
- Determine the most common pizza sizes
- Find peak ordering hours
- Analyze category-wise sales
- Calculate daily and cumulative revenue
- Rank the top-performing pizza types

---

## 🛠️ Tech Stack

- **Database:** MySQL
- **Tool:** MySQL Workbench
- **Language:** SQL
- **Version Control:** Git & GitHub

---

## 📂 Dataset

The project uses four tables:

| Table | Description |
|--------|-------------|
| orders | Stores order date and time |
| order_details | Stores pizza quantities ordered |
| pizzas | Stores pizza size and price |
| pizza_types | Stores pizza names, categories, and ingredients |

---

## 🗂️ Project Structure

```
Pizza-Sales-SQL-Analysis/
│
├── Data/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── Table/
│   └── schema.sql
│
├── Queries/
│   ├── 01_Basic_Queries.sql
│   ├── 02_Intermediate_Queries.sql
│   └── 03_Advanced_Queries.sql
│
├── img/
│   └── Query_Outputs/
│
└── README.md
```

---

## 📊 SQL Concepts Used

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- Aggregate Functions
- INNER JOIN
- Subqueries
- Window Functions
- RANK()
- SUM() OVER()
- Aliases

---

## 🚀 How to Run

1. Create a database named `pizzahut`.
2. Execute `Database/schema.sql`.
3. Import the CSV files from the `Data` folder.
4. Run the SQL queries from the `Queries` folder.

---

## 📌 Key Learnings

- Writing SQL queries
- Working with multiple table joins
- Using aggregate functions
- Applying window functions
- Performing business-oriented data analysis
- Organizing SQL projects for GitHub
