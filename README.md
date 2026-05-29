# Zepto-SQL-Analysis


# Zepto Inventory Data Analysis using PostgreSQL

## Project Overview

This project analyzes a real-world Zepto inventory dataset using PostgreSQL. The objective is to perform data cleaning, exploratory data analysis (EDA), and business-focused analysis to derive actionable insights from product, pricing, discount, and inventory data.

## Dataset

The dataset contains product-level inventory information including:

* Product Name
* Category
* MRP
* Discount Percentage
* Selling Price
* Available Quantity
* Product Weight
* Stock Availability

## Project Workflow

### 1. Database Design

* Created a PostgreSQL database and inventory table structure.
* Imported and validated raw inventory data.

### 2. Data Exploration

* Analyzed total records and product categories.
* Identified null values and duplicate product names.
* Evaluated stock availability across categories.

### 3. Data Cleaning

* Removed records with invalid pricing.
* Converted pricing values from paise to rupees.
* Validated data consistency before analysis.

### 4. Business Analysis

Key business questions answered:

* Which products offer the highest discounts?
* Which high-value products are currently out of stock?
* What is the estimated revenue potential by category?
* Which categories provide the highest average discounts?
* Which products offer the best value based on price per gram?
* How can products be segmented based on weight?
* What is the total inventory weight available in each category?

## SQL Concepts Used

* Data Cleaning
* Aggregate Functions
* GROUP BY
* ORDER BY
* CASE Statements
* Filtering and Sorting
* DISTINCT
* Data Validation

## Key Insights

* Identified top-discounted products across categories.
* Estimated category-wise revenue contribution.
* Highlighted inventory risks through out-of-stock analysis.
* Evaluated pricing efficiency using price-per-gram calculations.
* Segmented products into Low, Medium, and Bulk categories for inventory planning.


## Future Enhancements

* Add Common Table Expressions (CTEs)
* Implement Window Functions for ranking analysis
* Build Power BI dashboard using analyzed data
* Create inventory forecasting models using Python
