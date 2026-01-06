# Task 3 — SQL for Data Analysis

This project focuses on analyzing an E-commerce sales dataset using MySQL.
The entire workflow includes importing the dataset, writing SQL queries for business insights, and optimizing performance using views and indexes.

# Dataset

Dataset Name: Retail Sales (sales_data_sample.csv)
Tool Used: MySQL

# Steps Performed

# Step 1 — Import CSV into SQL Database

Created database and table structure.

Imported dataset into MySQL.

# Step 2 — Basic SELECT Queries

Viewed sample records

Filtered rows using WHERE condition

Sorted results using ORDER BY

# Step 3 — GROUP BY Analysis

Calculated total sales by product

Found average order value by year

# Step 4 — JOINS

Joined sales table with a customer table to analyze regional sales distribution

# Step 5 — Subqueries

Extracted orders with higher-than-average sales

# Step 6 — Aggregate Functions

Used SUM, COUNT, AVG, MAX, MIN for business insights

# Step 7 — Views Creation

View for monthly sales trends

View for customer sales summary

# Step 8 — Index Optimization

Created indexes to improve performance on high-usage columns

# Key Insights
Insight	Observation
Best-selling class	Classic Cars generated the highest sales
Market performance	USA performed the highest overall
Seasonal trend	Highest number of orders occur mid-year
Customer activity	Lowest sales observed in late-year months
Index effect	Indexing significantly improved query speed

# Learnings & SQL Skills Used

SELECT, WHERE, ORDER BY, GROUP BY

Aggregate functions: SUM, AVG, COUNT, MAX, MIN

INNER JOIN, LEFT JOIN, subqueries

View creation for analytical reporting

# Repository Structure

# SQL-Data-Analysis-Task-3
 ┣ queries.sql
 ┣ views.sql
 ┣ indexes.sql
 ┣ screenshots/
 ┣ report.pdf
 ┗ README.md


# Summary

This project demonstrates how SQL can be used to transform raw tabular data into actionable business insights.
By applying analytical queries, creating reusable views, and improving efficiency with indexes, data becomes easier to interpret for decision-making.
