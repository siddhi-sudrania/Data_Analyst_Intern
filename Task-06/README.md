Sales Trend Analysis Using SQL Aggregations
Objective
Analyze monthly revenue and order volume using SQL queries.

Dataset
Table: online_sales
Columns: order_date, amount, product_id, order_id

Tools Used
MySQL
Key Queries
Monthly revenue and order volume using SUM() and COUNT(DISTINCT order_id)
Top 3 months by total revenue using ORDER BY ... DESC LIMIT 3
Concepts Used
GROUP BY with YEAR and MONTH
Aggregate functions: SUM, COUNT
Sorting with ORDER BY
