# E-Commerce Sales & Customer Behavior Analysis

## Project Overview

This project analyzes nearly 100,000 e-commerce orders to understand
purchasing patterns, payment preferences, delivery performance, and
customer satisfaction.

The project is being developed as an end-to-end data analytics project,
progressively using Excel, MySQL, Python, and Power BI to transform raw
order data into meaningful business insights.

## Dataset

The project uses an e-commerce order-level dataset containing
99,441 records and 15 variables related to:

- Order information
- Customer identifiers
- Order status
- Payment methods and installments
- Order and freight values
- Delivery dates
- Customer review scores

## Project Objectives

- Understand the structure and quality of the dataset
- Perform data profiling and quality analysis
- Clean and preprocess the data
- Analyze sales and purchasing behavior
- Analyze payment methods and order values
- Study delivery performance and delivery delays
- Explore customer review and satisfaction patterns
- Identify relationships between delivery performance and reviews
- Generate meaningful business insights
- Build an interactive Power BI dashboard
- Develop an end-to-end analytics workflow using multiple tools

## Tools & Technologies

### Programming
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Database & Querying
- MySQL

### Data Analysis & Visualization
- Microsoft Excel
- Power BI

## Key Analysis Areas
- Sales and order value analysis
- Payment behavior
- Installment patterns
- Delivery performance
- Delivery delays
- Customer review scores
- Freight and order value analysis
- Relationship between delivery performance and customer satisfaction

## Project Progress 

###  Dataset Understanding
- Loaded and explored the e-commerce dataset.
- Examined dataset dimensions, columns, data types, and basic statistics.
- Checked unique identifiers and duplicate records.

###  Data Quality Analysis
- Investigated missing values and their distribution.
- Examined numerical columns and categorical values.
- Identified data-quality issues requiring further investigation.

###  Data Cleaning and Preprocessing
- Created a working copy of the original dataset.
- Standardized categorical values and converted date columns to datetime format.
- Investigated missing values and potential data inconsistencies.

###  Feature Engineering
- Created delivery-related features, including delivery duration and delivery delay.
- Classified delivery performance as Early, On Time, Late, or Not Delivered.
- Extracted year, month, day, weekday, and hour from purchase timestamps.

###  Sales and Purchase Behavior Analysis
- Analyzed total sales value, average order value, and median order value.
- Examined monthly, daily, and hourly purchasing patterns.
- Investigated the number of items per order.

###  Payment Behavior Analysis
- Compared payment methods by order count and sales value.
- Analyzed average order value across payment methods.
- Examined installment preferences.

###  Delivery Performance Analysis
- Compared actual delivery duration with expected delivery duration.
- Analyzed early, on-time, late, and not-delivered orders.
- Examined delivery performance across different periods and order statuses.

###  Customer Satisfaction Analysis
- Examined the distribution of customer review scores.
- Compared average review scores across payment methods, delivery categories, and order statuses.
- Investigated missing and fractional review scores.

### Advanced EDA and Visualization
- Compared monthly order counts across years.
- Investigated missing price values in October 2018.
- Compared customer review scores across delivery-performance categories.
- Created a reusable Python function for category-based summaries.
- Identified the top 10 orders by price.

### Key Findings
- Credit card was the most frequently used payment method.
- Most recorded reviews had a score of 5.
- Orders delivered early had higher average review scores than late-delivered orders.
- October 2018 contained four orders with missing price values, so their sales value could not be determined from the available price data.
- Some years contain partial-year data, which requires caution when comparing monthly order trends.

### Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git and GitHub

### Current Progress
Completed the initial data exploration, preprocessing, feature engineering, sales analysis, payment analysis, delivery analysis, customer satisfaction analysis, and advanced exploratory data visualization. The next phase will focus on Excel-based analysis using the same dataset.
