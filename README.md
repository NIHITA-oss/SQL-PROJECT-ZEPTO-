Zepto SQL Data Analysis Project(Impact: This project demonstrates inventory optimization, pricing strategy, and revenue analysis using SQL, reflecting the workflow of a real data analyst in e-commerce.)

A real-world e-commerce inventory analysis project using SQL, based on a dataset inspired by Zepto – one of India’s fastest-growing quick-commerce platforms. This project simulates an end-to-end analyst workflow, from raw data exploration to actionable business insights.

Dataset Overview

Source: Kaggle 

Rows: Each SKU of a product (same product may have multiple SKUs for different sizes/weights/discounts)

Key Columns: sku_id, name, category, mrp, discountPercent, discountedSellingPrice, availableQuantity, weightInGms, outOfStock, quantity

Project Workflow

Table Creation & Data Import

Created PostgreSQL table with proper data types

Imported CSV (UTF-8) into the database

Data Exploration

Counted records, checked nulls, and sampled data

Identified in-stock vs out-of-stock products and duplicate SKUs

Data Cleaning

Removed rows with zero prices

Converted prices from paise → ₹

Business Insights

Top products by discount and price per gram

High-MRP products out of stock

Potential revenue per category

Top categories with highest average discounts

Inventory weight analysis

Skills Highlighted

SQL: CREATE TABLE, GROUP BY, HAVING, COUNT, SUM, ORDER BY

Data Cleaning & Transformation

Business-focused Analytics & Reporting
