# Sales Insights Dashboard Using Power BI and SQL

## Project Overview

This project focuses on analyzing sales performance for AtliQ Hardware, a computer hardware and peripherals company operating across multiple regions in India. The objective is to transform raw sales data into actionable business insights using SQL, Power BI, Power Query, and DAX.

The dashboard enables management to monitor revenue, profitability, customer performance, product performance, and market trends through an interactive Business Intelligence solution.


## Problem Statement

AtliQ Hardware's Sales Director faced difficulties in understanding the company's sales performance due to scattered Excel reports and manual reporting from regional managers.

The lack of a centralized reporting system made it difficult to:

* Track sales performance across markets
* Identify profitable customers and products
* Monitor revenue and profit trends
* Make data-driven business decisions
* Reduce time spent on manual reporting

To address these challenges, an interactive Power BI dashboard was developed to provide real-time sales insights and support strategic decision-making.


## Business Objectives

* Analyze revenue, sales quantity, and profit margin.
* Identify top-performing customers and products.
* Evaluate market-wise profitability.
* Track revenue trends over time.
* Measure customer-type contribution to revenue.
* Enable faster and data-driven decision-making.


## AIMS Grid

### Purpose

Unlock sales insights that were previously hidden and automate reporting processes to reduce manual effort.

### Stakeholders

* Sales Director
* Marketing Team
* Customer Service Team
* Data & Analytics Team
* IT Team

### End Result

An automated dashboard providing quick and accurate business insights.

### Success Criteria

* Improve decision-making through data-driven insights.
* Reduce manual reporting effort.
* Save business time spent on data collection and reporting.
* Support cost optimization initiatives.

## Dataset Information

The project uses a MySQL database containing the following tables:

* Customers
* Products
* Transactions
* Markets
* Date


## Tools & Technologies

* Power BI Desktop
* MySQL
* SQL
* Power Query
* DAX (Data Analysis Expressions)


## Project Workflow

### 1. Data Discovery

* Explored database structure.
* Identified business requirements.
* Understood relationships between tables.

### 2. Data Analysis Using SQL

* Imported database into MySQL.
* Performed exploratory analysis.
* Executed SQL queries to identify trends and business insights.

### 3. Data Cleaning & Transformation

* Connected MySQL with Power BI.
* Loaded data into Power BI Desktop.
* Cleaned and transformed data using Power Query.
* Handled inconsistencies and prepared data for modeling.

### 4. Data Modeling & DAX

Created DAX measures for:

* Revenue
* Sales Quantity
* Profit Margin
* Profit Margin %
* Revenue Contribution %
* Profit Contribution %

### 5. Dashboard Development

Built interactive dashboards for:

* Revenue Analysis
* Profitability Analysis
* Customer Analysis
* Product Analysis
* Market Analysis
* Revenue Trend Analysis


## Key Performance Indicators (KPIs)

* Total Revenue
* Total Sales Quantity
* Total Profit Margin
* Profit Margin %
* Revenue Contribution %
* Profit Contribution %


## Business Insights

### Revenue & Profitability

* Total Revenue generated: ₹985M
* Total Profit Margin: ₹24.7M
* Profit Margin Percentage: 2.5%
* Total Sales Quantity: 2M units

### Market Analysis

* Delhi NCR generated the highest revenue contribution (52.8%).
* Bhubaneshwar achieved the highest profit margin percentage (10.48%).
* Mumbai contributed the highest share of total profit.
* Bengaluru recorded the lowest profit margin.

### Customer Analysis

* Electricalsara Stores was the highest revenue-generating customer with ₹413M revenue.

### Product Analysis

* Prod318 was the highest revenue-generating product with ₹69M revenue.

### Customer Type Analysis

* E-commerce customers generated the highest revenue contribution.

### Revenue Trends

* Revenue showed a declining trend from 2017 to 2020.
* Revenue dropped significantly during June 2020.
* Profit margins were lowest during April 2020.

## Project Files

* Sales_Insights.pbix
* db_dump.sql
* SQL Analysis Queries
* Project Documentation


## Conclusion

This project demonstrates how Business Intelligence tools can transform raw sales data into meaningful insights. By integrating SQL, Power BI, Power Query, and DAX, the dashboard provides a centralized reporting solution that helps stakeholders monitor performance, identify opportunities, and make informed business decisions.
