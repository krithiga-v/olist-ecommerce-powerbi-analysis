# Olist E-Commerce Power BI Analysis

An interactive Power BI dashboard analyzing sales, customers, products, sellers, payments, and delivery performance using the Olist Brazilian E-Commerce Public Dataset.

---

## 📊 Project Overview

This project uses **Microsoft Power BI** to transform raw e-commerce data into an interactive business intelligence dashboard.

The analysis focuses on understanding:

- Sales and revenue performance
- Order trends and growth
- Delivery and operational performance
- Customer purchasing behavior
- Product and category performance
- Seller performance and marketplace activity
- Payment method usage
- Geographic distribution of customers and sellers

The final report contains **6 interactive Power BI pages**, designed to provide both high-level business insights and detailed analysis.

---

## 📑 Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of the Olist marketplace.

**Key areas:**
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Revenue trends
- Top product categories
- Revenue by state
- Delivery performance
- Orders by year and quarter

### 2. Sales & Revenue Analysis

Focuses on revenue generation, order trends, and category performance.

**Key areas:**
- Monthly Revenue & Orders
- Revenue Growth
- Revenue contribution by category
- Revenue vs Order Volume
- Payment method usage
- Average Order Value by category
- Top-performing product categories

### 3. Operations & Delivery Analysis

Analyzes order fulfillment and delivery performance.

**Key areas:**
- Average Delivery Days
- Average Estimated Delivery Days
- Delivery Variance
- On-Time Delivery %
- Delivery performance by year
- Actual vs Estimated Delivery Days
- Average Order Value by state
- Average Freight Value by state

### 4. Customer & Purchase Analysis

Analyzes customer behavior and purchasing patterns.

**Key areas:**
- Total Customers
- Average Order Value
- Average Orders per Customer
- Repeat Customer %
- One-Time vs Repeat Customers
- New Customers by year and quarter
- Customer distribution by state
- Purchase behavior over time

### 5. Product Performance

Examines product volume, pricing, and category performance.

**Key areas:**
- Total Products
- Total Units Sold
- Average Product Price
- Average Freight per Item
- Top 10 Categories by Units Sold
- Top 10 Categories by Average Product Price

### 6. Seller & Marketplace Analysis

Analyzes seller contribution and marketplace activity.

**Key areas:**
- Total Sellers
- Average Items per Seller
- Average Revenue per Seller
- Average Orders per Seller
- Top 10 Sellers by Revenue
- Seller activity over time
- Orders by Seller State
- Marketplace coverage

---

## 💡 Key Business Insights

The analysis produced several useful business insights:

- The Olist marketplace generated approximately **13.59M in total revenue** across approximately **99K orders**.
- The dataset contains approximately **96K customers**.
- The overall Average Order Value is approximately **136.68**.
- **Health & Beauty** was one of the strongest revenue-generating product categories.
- **Credit card** was the dominant payment method by number of orders.
- Average actual delivery time was substantially lower than the estimated delivery time.
- Repeat customers represented only a small percentage of the customer base, highlighting an opportunity to improve customer retention.
- Seller activity increased significantly as the marketplace expanded through 2017 and 2018.
- Geographic analysis shows significant marketplace activity concentrated in major Brazilian states.

---

## 🗂️ Dataset

This project uses the:

**Olist Brazilian E-Commerce Public Dataset**

The dataset contains information about:

- Orders
- Order Items
- Payments
- Reviews
- Customers
- Products
- Sellers
- Geolocation

The original dataset is **not included in this repository**.

---

## 🏗️ Data Model

The Power BI report uses a structured **star-schema data model**.

### Fact Tables

- `FactOrders`
- `FactOrderItems`
- `FactPayments`
- `FactReviews`

### Dimension Tables

- `DimCustomer`
- `DimProduct`
- `DimSeller`
- `DimDate`
- `DimGeography`

This structure separates transactional data from descriptive dimensions and supports analysis across multiple business areas.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Git**
- **Git LFS**
- **GitHub**

---

## 📈 Power BI Features Used

- Interactive slicers
- KPI cards
- Line charts
- Column charts
- Bar charts
- Treemaps
- Scatter plots
- Donut charts
- Maps
- Top N filtering
- Data labels
- Conditional formatting
- Time-based analysis
- DAX measures
- Star-schema data modeling

---

## 🎯 Business Questions

This project was designed to answer questions such as:

1. How is revenue changing over time?
2. Which product categories generate the most revenue?
3. Which categories have the highest sales volume?
4. What payment methods are most commonly used?
5. How efficiently are orders being delivered?
6. How does actual delivery time compare with estimated delivery time?
7. How many customers make repeat purchases?
8. Where are customers geographically concentrated?
9. Which product categories have higher average prices?
10. Which sellers contribute the most revenue?
11. How is seller activity changing over time?
12. Which states have the highest marketplace activity?

---

## 🔄 Project Workflow

The project follows a complete data analytics workflow:

**Raw Data → Data Cleaning → Data Transformation → Data Modeling → DAX Measures → Dashboard Development → Business Insights**

### 1. Data Preparation

Raw Olist datasets were cleaned and transformed using Power Query.

### 2. Data Modeling

The datasets were organized into fact and dimension tables using a star-schema approach.

### 3. DAX Analysis

Measures were created for important business metrics such as:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Revenue Growth
- Total Products
- Total Units Sold
- Average Product Price
- Average Freight
- Total Sellers
- Seller Activity
- Delivery Performance
- Customer Purchase Metrics

### 4. Dashboard Development

The analysis was presented through six interactive Power BI pages covering sales, operations, customers, products, and sellers.

---

## 📁 Repository Structure

```text
olist-ecommerce-powerbi-analysis/
│
├── README.md
├── olist.pbix
├── .gitattributes
│
├── screenshots/
│   ├── page-1.png
│   ├── page-2.png
│   ├── page-3.png
│   ├── page-4.png
│   ├── page-5.png
│   └── page-6.png
│
├── data/
│   └── README.md
│
└── documentation/
    └── project-notes.md

---

## 📚 Learning Outcomes

This project provided practical experience in:

- Data cleaning and transformation using Power Query
- Designing a star-schema data model
- Creating analytical DAX measures
- Building interactive Power BI dashboards
- Working with multiple related datasets
- Time-based sales analysis
- Customer and seller analysis
- Geographic analysis
- KPI design
- Business-focused data visualization
- Git and GitHub project management
- Using Git LFS for large Power BI files

---

## 🚀 Future Improvements

Potential future improvements include:

- Customer Lifetime Value analysis
- Advanced customer segmentation
- Seller performance scoring
- More detailed geographic analysis
- Profitability analysis
- Additional operational KPIs
- Automated data refresh
- Advanced forecasting
- Predictive analytics

---

## 👤 Author

**Krithiga V**

This project was created as part of my **Data Analytics and Business Intelligence portfolio**.

---

## ⭐ Project Highlights

- **6 Power BI Dashboard Pages**
- **Multiple E-Commerce Fact & Dimension Tables**
- **DAX-Based Business Metrics**
- **Interactive Visual Analysis**
- **Customer, Product & Seller Insights**
- **Sales & Operational Performance Analysis**
- **GitHub + Git LFS Project Management**

---

If you find this project useful or interesting, feel free to explore the dashboard and analysis.
