# Restaurant-Orders-SQL-Project
🍽️ Restaurant Orders Data Analysis

This project analyzes a quarter’s worth of restaurant orders from a fictitious international cuisine restaurant. The dataset contains multiple relational tables with 12,266 records and 8 fields, stored in MySQL format.
The goal is to explore menu data, analyze customer orders, and uncover insights into customer behavior and spending trends.

📊 Dataset Overview

Source: Provided fictitious dataset
Format: MySQL, multiple tables

Tables:

menu_items → Contains details about each dish (name, category, price)
order_details → Contains transactional data of customer orders
Records: 12,266
Fields: 8

🎯 Objectives
Objective 1: Explore the Menu Items Table

Find total number of menu items.
Identify least and most expensive items.
Explore Italian dishes: count, least expensive, most expensive.
Find number of dishes in each category and their average price.

Objective 2: Explore the Orders Table

Find the date range of available orders.
Calculate the total number of orders and items ordered.
Identify orders with the highest number of items.
Find how many orders had more than 12 items.

Objective 3: Analyze Customer Behavior

Join menu_items and order_details to form a combined dataset.
Identify least and most ordered items (and their categories).
Find Top 5 highest-spend orders.
Explore detailed breakdown of the single highest-spend order.
Bonus: View item details of Top 5 spend orders.

🛠️ Tools & Technologies

Database: MySQL
Queries: SQL (JOIN, GROUP BY, Aggregations, etc.)
Analysis: Exploratory data analysis through SQL queries

📌 Sample Insights (Expected Outcomes)

Total number of dishes on the menu
Least and most expensive dishes overall & by category
Most frequently ordered dishes and categories
Highest-spend orders and their breakdown
Total revenue and customer spending trends

❓ Final Project Question

💡 How much was the most expensive order in the dataset?
(Answer found by summing up items per order after joining both tables.)

📂 Repository Structure
📁 Restaurant-Orders-Analysis
 ┣ 📄 README.md   # Project Documentation
 ┣ 📄 queries.sql # All SQL queries written for objectives
 ┣ 📊 insights.pdf # Summary of insights (optional visualization)
 ┗ 📂 dataset     # MySQL dataset files

🚀 How to Use

Import dataset into MySQL.
Run queries from queries.sql step by step.
Compare results with project objectives.
Document insights for reporting or dashboard building.

🌟 Key Learning Outcomes

Hands-on practice with SQL joins, aggregations, and filters.
Understanding of menu pricing & customer ordering behavior.
Real-world scenario of analyzing restaurant business performance.

👉 This project is a part of my SQL Data Analytics portfolio.
