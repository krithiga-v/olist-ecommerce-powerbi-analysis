# Project Documentation

## Project Objective

The objective of this project is to analyze the Olist Brazilian e-commerce dataset using Power BI and develop an interactive business intelligence dashboard.

The analysis focuses on sales, revenue, customers, products, delivery performance, and seller performance.

## Dashboard Pages

### 1. Executive Overview
Provides a high-level overview of revenue, orders, customers, sales trends, product categories, geography, and delivery performance.

### 2. Sales & Revenue Analysis
Analyzes revenue trends, order volume, revenue growth, product categories, payment methods, and average order value.

### 3. Operations & Delivery Analysis
Analyzes delivery time, estimated versus actual delivery, on-time performance, delivery status, freight value, and state-level operational performance.

### 4. Customer & Purchase Analysis
Analyzes customer distribution, purchase behavior, average order value, repeat customers, and new customer trends.

### 5. Product Performance
Analyzes product volume, product pricing, freight costs, and product category performance.

### 6. Seller & Marketplace Analysis
Analyzes seller performance, seller revenue, seller activity, marketplace coverage, and seller distribution.

## Data Model

The Power BI model follows a star-schema approach with fact and dimension tables.

### Fact Tables
- FactOrders
- FactOrderItems
- FactPayments
- FactReviews

### Dimension Tables
- DimCustomer
- DimProduct
- DimSeller
- DimDate
- DimGeography

## Tools Used

- Power BI Desktop
- DAX
- Power Query
- Microsoft Excel
- GitHub
- Git LFS

## Key Analysis Areas

- Revenue and sales trends
- Order volume
- Average order value
- Customer behavior
- Product category performance
- Delivery performance
- Seller performance
- Payment methods
- Geographic distribution

## Project Workflow

1. Imported the Olist dataset into Power BI.
2. Cleaned and transformed the data using Power Query.
3. Designed a star-schema data model.
4. Created calculated measures using DAX.
5. Developed six interactive dashboard pages.
6. Applied consistent visual design and formatting.
7. Published the project files and dashboard screenshots to GitHub.
