# 📊 Retail Performance Analytics Dashboard (Power BI)

## 📌 Project Overview

The Retail Performance Analytics Dashboard is an interactive Business Intelligence solution developed using Power BI to analyze sales performance, profitability, regional performance, product sales, and store-level analytics.

The dashboard provides management with a centralized reporting platform to monitor key business KPIs and make data-driven decisions.

---

# 🎯 Business Objective

The objective of this dashboard is to:

* Monitor sales and profitability.
* Analyze revenue trends over time.
* Track regional sales performance.
* Analyze product contribution.
* Evaluate store performance.
* Identify top and bottom-performing products.
* Improve business visibility through interactive reporting.

---

# 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* Star Schema Design
* Interactive Slicers
* Drillthrough
* Dynamic Titles

---

# 📂 Dataset Information

The project consists of:

## Fact Table

### Fact_Sales

* Order ID
* Order Date
* Customer ID
* Product ID
* Store ID
* Region
* Category
* Product Name
* Quantity
* Unit Price
* Sales Amount
* Cost Amount
* Profit Amount

---

## Dimension Tables

### Dim_Product

* Product ID
* Category
* Product Name

### Dim_Store

* Store ID
* Store Name
* Region

### Dim_Calendar

* Date
* Year
* Month
* Month Number
* Quarter

---

# ⭐ Data Model

A Star Schema was implemented.

### Relationships

* Dim_Calendar → Fact_Sales
* Dim_Product → Fact_Sales
* Dim_Store → Fact_Sales

---

# 📏 DAX Measures Created

## Revenue Measures

* Total Sales

## Profit Measures

* Total Profit
* Profit Margin %

## Order Measures

* Total Orders
* Average Order Value

## Dynamic Features

* Dynamic Visual Titles
* Drillthrough Navigation

---

# 📈 Report Pages

## Executive Overview

Includes:

* Total Sales KPI
* Total Profit KPI
* Profit Margin KPI
* Total Orders KPI
* Average Order Value KPI
* Sales Trend
* Profit Trend
* Regional Performance
* Category Contribution

---

## Product & Store Analysis

Includes:

* Top 10 Products by Sales
* Bottom 10 Products by Sales
* Top 10 Stores by Sales
* Product Profitability Matrix
* Conditional Formatting

---

# 📊 Key Business Insights

* Monitor overall business performance using KPI cards.
* Analyze regional contribution to total sales.
* Identify top-performing products.
* Track store-wise business performance.
* Evaluate product profitability using matrix analysis.
* Compare sales and profit trends across time periods.

---

# ✨ Advanced Power BI Features

* Interactive Slicers
* Dynamic Titles
* Multi-Page Navigation
* Drillthrough
* Conditional Formatting
* Data Modeling
* DAX Calculations

---

# 🚀 Skills Demonstrated

* Power BI
* Power Query
* DAX
* Data Modeling
* Business Intelligence
* Dashboard Design
* Data Visualization
* KPI Reporting
* Sales Analytics
* Retail Analytics

---

# 📸 Dashboard Screenshots

## Executive Overview

(Add Screenshot Here)

---

## Product & Store Analysis

(Add Screenshot Here)

---

# 👨‍💻 Author

### Jagadeesvar M

**Executive - MIS**

* Power BI Developer
* Excel Dashboard Developer
* Data Analytics Enthusiast

---

# ⭐ If you found this project useful, consider giving this repository a star.
