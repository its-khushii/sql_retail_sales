 Retail Sales Analysis (SQL Project)


 Overview

This project focuses on analyzing retail sales data using SQL. It covers data cleaning, exploration, and solving real-world business problems through structured queries.
The goal of this project is to extract meaningful insights such as customer behavior, sales trends, and category performance.

The dataset contains transactional retail data with the following columns:

transactions_id – Unique ID for each transaction
sale_date – Date of sale
sale_time – Time of sale
customer_id – Unique customer identifier
gender – Customer gender
age – Customer age
category – Product category
quantity – Number of items sold
price_per_unit – Price of one unit
cogs – Cost of goods sold
total_sale – Total transaction value

Project Steps

1. Data Preparation 
Created table retail_sales
Defined appropriate data types
Checked total records

3. Data Cleaning
Identified NULL values in key columns
Removed incomplete records using DELETE

5. Data Exploration
Total number of sales
Number of unique customers
Available product categories

 Key Questions Solved:

Retrieve all sales on a specific date
Filter transactions based on category and quantity
Calculate total sales per category
Find average age of customers by category
Identify high-value transactions (>1000)
Count transactions by gender and category
Find best-selling month in each year
Identify top 5 customers by total spending
Count unique customers per category
Analyze sales distribution by time shifts (Morning, Afternoon, Evening)
