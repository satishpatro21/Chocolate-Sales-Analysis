
# Chocolate Sales Analysis: SQL Data Cleaning & Querying

This project showcases a complete end-to-end data workflow, from processing raw sales data to executing complex business intelligence queries. The dataset contains international sales records for a chocolate manufacturer, including details on sales representatives, product categories, geographic regions, and shipment volumes.

## Project Overview

The goal of this project was to transform a "dirty" dataset of chocolate transactions into a structured SQL database to answer key business questions, such as identifying top performers, analyzing regional market penetration, and categorizing sales volume.

## Tech Stack

* **Language:** SQL (MySQL/PostgreSQL compatible)
* **Data Format:** CSV (Raw Data), SQL (Database Schema & Queries)
* **Tools:** Relational Database Management System (RDBMS)

## Dataset Description

The dataset includes the following attributes:

* **Sales Person:** The representative responsible for the transaction.
* **Country:** The international market (India, UK, USA, Canada, Australia, New Zealand).
* **Product:** The specific chocolate variety (e.g., "99% Dark & Pure", "Mint Chip Choco").
* **Date:** Transaction timestamp.
* **Amount:** Total revenue per sale (cleaned from currency strings to decimal format).
* **Boxes Shipped:** Physical volume of the shipment.

## Key SQL Implementations

The project includes a series of analytical queries designed to solve specific business problems:

1. **Filtering & Conditional Logic:** Extracting high-value sales specifically in the Indian market.
2. **Aggregation & Grouping:** Calculating total revenue per salesperson and transaction counts per country.
3. **Statistical Analysis:** Determining average shipment sizes per product and identifying sales that exceed the company-wide average.
4. **Pattern Matching:** Using `LIKE` operators to isolate specific product lines (e.g., all 'Choco' branded items).
5. **Data Categorization:** Using `CASE` statements to segment transactions into 'Large', 'Medium', and 'Small' tiers based on revenue.

## Sample Insights

* **Top 10 Performance:** A query to instantly identify the largest transactions by revenue.
* **Product Popularity:** Analysis of the average boxes shipped to help with inventory forecasting.
* **Sales Tiers:** Automated categorization of sales to help marketing teams target specific customer segments.

## Repository Structure

* `ChocolateSales.sql`: Contains the database schema (DDL) and the full suite of analytical queries.
* `Chocolate_Sales_Dates_And_Amounts_Cleaned.csv`: The cleaned source data used for the analysis.
