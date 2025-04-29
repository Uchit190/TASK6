# 🧮 Task 6: Sales Trend Analysis Using Aggregations

## 📌 Internship: Data Analyst at CODTECH IT Solutions Pvt. Ltd.

This task involved analyzing monthly sales performance using SQL aggregation techniques. I used MySQL to group and summarize the data by month and year, helping identify trends in revenue and order volume.

---

## 📊 Objective

- Analyze **monthly revenue** and **order volume**.
- Practice using **aggregate functions** and **time-based grouping** in SQL.

---

## 🛠 Tools Used

- MySQL Workbench
- SQL Queries
- GitHub for version control

---

## 📁 Dataset

Table: `online_sales`  
Fields:
- `order_id` (INT)
- `order_date` (DATE)
- `amount` (DECIMAL)
- `product_id` (INT)

---

## 📄 SQL Tasks Performed

- Created a sample dataset with 30 rows spanning multiple months.
- Grouped records by `YEAR(order_date)` and `MONTH(order_date)`.
- Used:
  - `SUM(amount)` to calculate total monthly revenue.
  - `COUNT(DISTINCT order_id)` to calculate monthly order volume.
- Ordered results chronologically using `ORDER BY`.

---

## 📌 Output Sample

| order_year | order_month | total_revenue | order_volume |
|------------|-------------|-
