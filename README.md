TASK 6: Sales Trend Analysis Using Aggregations

Objective:
Analyze monthly revenue and order volume using SQL aggregation functions.

Tools Used:
MySQL

A) Steps Performed

a. Database and Table Creation
A new database named online_sales was created, followed by a table orders with four columns: order_id, oreder_date, amount, and product_id.

b. Data Insertion
Inserted sample data for the year 2023 containing 24 orders (two per month).
This data was used to simulate monthly sales performance across the year.

c. Index Creation (optional)
An index was added on oreder_date to optimize query performance.

d. Aggregation Query Execution
Used MySQL’s built-in YEAR() and MONTH() functions to extract year and month from the order date.
Then used:

SUM(amount) to calculate total monthly revenue

COUNT(DISTINCT order_id) to calculate total monthly order volume

The data was grouped and sorted by year and month for a clear trend overview.

B) SQL Concepts Applied

- GROUP BY
- SUM()
- COUNT(DISTINCT....)
- YEAR() / MONTH()
- ORDER BY 
- WHERE
C) Insights Drawn

    -The highest revenue was recorded in December (₹9,500).
    -The lowest sales months were January and June.
    -Average monthly revenue was approximately ₹5,200.
    -Consistent order volume (2 per month) shows steady transaction frequency.
    -Such trends help businesses identify seasonal peaks and optimize marketing or inventory.
