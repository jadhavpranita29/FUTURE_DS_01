# Business Sales Analysis

# Task Overview

This task focuses on building an interactive Business Sales Dashboard using Power BI to analyze sales performance across time, countries, and products.
The dashboard helps stakeholders understand revenue trends, top-selling products, and regional performance to support data-driven decision-making.

#  Dataset Description

The dataset contains transactional sales data with the following columns:

InvoiceNo – Unique invoice number

StockCode – Product code

Description – Product description

Quantity – Units sold

InvoiceDate – Date of transaction

UnitPrice – Price per unit

CustomerID – Unique customer identifier

Country – Customer country

TotalPrice – Calculated as Quantity × UnitPrice

 # Objectives

Analyze total revenue and quantity sold

Identify top-selling products

Understand revenue trends over time

Compare sales performance across countries

Create a clear and interactive Power BI dashboard

# Data Preparation Steps

Removed missing and invalid values

Converted data types (dates, numeric fields)

Created calculated column:

TotalPrice = Quantity × UnitPrice

Created Date hierarchy (Year, Month)

Validated country and product data

📐 Key Measures (DAX Used)
Total Revenue = SUM(Sales[TotalPrice])

Total Quantity Sold = SUM(Sales[Quantity])

Total Customers = DISTINCTCOUNT(Sales[CustomerID])


# Summary Table

Displays:

Country

Revenue

Total Quantity Sold

# Key Insights

United Kingdom is the highest revenue-generating country

Sales show a strong upward trend toward the end of the year

A small number of products contribute to high sales volume

Some countries have low quantity but high revenue, indicating premium pricing

# Business Recommendations

Focus marketing efforts on high-performing countries

Maintain stock levels for top-selling products

Analyze low-performing regions for growth opportunities

Use seasonal trends to plan promotions and inventory

# conclusion

This Power BI dashboard provides a clear and interactive overview of business sales performance.
It helps stakeholders track revenue trends, identify top products, and evaluate regional performance, enabling better strategic decisions.

# Tools & Technologies

Power BI

DAX

Excel / CSV

Data Cleaning & Visualization
