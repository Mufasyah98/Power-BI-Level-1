# Power BI Level 1 Dataset
## Retail Sales Performance Analysis

## Overview

This dataset is designed for beginners learning Microsoft Power BI. It simulates the daily sales operations of a retail company that sells technology products across multiple countries and customer segments.

The objective is to help learners understand the complete Power BI workflow, including:

- Data loading
- Data modeling
- Relationship creation
- Data transformation
- DAX calculations
- Interactive dashboard development
- Business insight generation

---

# Business Scenario

ABC Retail is an international technology retailer selling computers, accessories, office equipment, networking devices, and storage products.

The management team wants to better understand sales performance by analysing:

- Which products generate the highest revenue
- Which categories are the most profitable
- Which customer segments contribute the most sales
- Sales performance across different countries and regions
- Discount impact on revenue
- Customer purchasing behaviour

As a Business Intelligence Analyst, your responsibility is to build an interactive Power BI dashboard that provides meaningful business insights to support management decision-making.

---

# Dataset Structure

The dataset contains **3 related tables**.

## 1. Products

Contains product information.

| Column | Description |
|----------|------------|
| ProductID | Unique product identifier |
| ProductName | Product name |
| Category | Product category |
| SubCategory | Product sub-category |
| UnitPrice | Selling price per unit |
| UnitCost | Product cost per unit |

---

## 2. Sales

Contains sales transaction records.

| Column | Description |
|----------|------------|
| OrderID | Sales transaction ID |
| OrderDate | Date of transaction |
| CustomerID | Customer identifier |
| ProductID | Product purchased |
| Quantity | Number of units sold |
| UnitPrice | Selling price |
| Discount | Discount percentage applied |
| TotalAmount | Total sales amount after discount |

---

## 3. Customers

Contains customer information.

| Column | Description |
|----------|------------|
| CustomerID | Customer identifier |
| CustomerName | Company name |
| Segment | Customer segment |
| Region | Geographic region |
| Country | Customer country |
| City | Customer city |

---

# Data Model

The dataset follows a simple Star Schema.

```
           Products
               |
               |
Sales ---------------- Customers
```

Relationships:

- Products[ProductID] → Sales[ProductID]
- Customers[CustomerID] → Sales[CustomerID]

---

# Business Questions

Build dashboards to answer the following questions:

### Sales Performance

- What is the total sales revenue?
- How many orders were completed?
- What is the total quantity sold?
- What is the average order value?

---

### Product Analysis

- Which products generate the highest sales?
- Which categories contribute the most revenue?
- Which products have the highest sales volume?
- Which products produce the highest gross profit?

---

### Customer Analysis

- Which customer segment contributes the most revenue?
- Which customers spend the most?
- Which region has the highest sales?
- Which country performs best?

---

### Time Analysis

- Monthly sales trend
- Quarterly sales trend
- Sales by year
- Peak sales month

---

### Discount Analysis

- Average discount given
- Products with highest discount
- Revenue before and after discount
- Impact of discount on sales

---

# Suggested KPIs

- Total Sales
- Total Orders
- Total Quantity Sold
- Average Order Value
- Gross Profit
- Gross Margin %
- Average Discount
- Number of Customers

---

# Recommended Dashboard Pages

## Page 1 — Executive Dashboard

Include:

- KPI Cards
- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Sales by Customer Segment

---

## Page 2 — Product Performance

Include:

- Top 10 Products
- Sales by Category
- Sales by Subcategory
- Profit by Product
- Quantity Sold

---

## Page 3 — Customer Analysis

Include:

- Sales by Customer
- Sales by Country
- Sales by Region
- Customer Segment Analysis
- Top Customers

---

## Page 4 — Time Intelligence

Include:

- Monthly Trend
- Quarterly Trend
- Running Total Sales
- Year-to-Date (YTD) Sales
- Month-over-Month Growth

---

# Suggested DAX Measures

Learners are encouraged to create measures such as:

- Total Sales
- Total Orders
- Total Quantity
- Average Order Value
- Gross Profit
- Gross Margin %
- Average Discount
- Total Customers
- Running Total Sales
- YTD Sales
- Sales Growth %

---

# Learning Objectives

After completing this project, learners should be able to:

- Import Excel datasets into Power BI
- Transform data using Power Query
- Build relationships between tables
- Create calculated measures using DAX
- Design professional dashboards
- Apply slicers and interactive filters
- Generate meaningful business insights
- Present data-driven recommendations

---

# Target Audience

This dataset is suitable for:

- Power BI Beginners
- Business Analysts
- Data Analysts
- Students
- Corporate Training Participants
- Self-Learning Projects
- Microsoft PL-300 Preparation

---

# Software Requirements

- Microsoft Power BI Desktop
- Microsoft Excel (optional)

---

# License

This dataset is intended for educational purposes, training sessions, workshops, and portfolio projects.
