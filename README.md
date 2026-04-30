# Northwind Traders Business Intelligence Dashboard

An end-to-end Business Intelligence project developed in **Power BI** using the Northwind Traders relational dataset. This project transforms raw business transaction data into an interactive 3-page executive dashboard that provides insights into sales performance, product intelligence, regional market share, shipping efficiency, and employee productivity.

---

## Project Objective

Northwind Traders, a global gourmet food supplier, requires an executive reporting solution capable of answering key business questions such as:

* How is revenue performing over time?
* Which product categories are the highest revenue drivers?
* How do discounts affect profitability?
* Which countries represent the strongest markets?
* How efficient are shipping providers?
* Which employees contribute the most to revenue?

This dashboard was built to provide a centralized, data-driven decision support system for executive management.

---

## Tools & Technologies Used

* Power BI Desktop
* Power Query Editor
* DAX (Data Analysis Expressions)
* Data Modeling (Star Schema)
* Interactive Dashboard Design

---

## Dataset Description

The project was built using seven interconnected CSV files:

* Orders
* Order Details
* Products
* Categories
* Customers
* Employees
* Shippers

These datasets collectively capture the complete sales and logistics workflow of Northwind Traders.

---

## Project Workflow

### 1. Data Cleaning & Preparation

* Imported all seven datasets into Power Query
* Standardized data types
* Removed duplicate records
* Trimmed text inconsistencies
* Handled blank shipped dates

### 2. Feature Engineering

Created custom analytical columns, including:

* Gross Revenue
* Discount Amount
* Net Revenue
* Delivery Days
* Delay Status
* Product Status
* Order Month / Order Year

### 3. Data Modeling

Built a star schema relationship model connecting fact and dimension tables for seamless cross-filtering and calculations.

### 4. DAX Measure Development

Developed reusable KPI measures such as:

* Total Net Revenue
* Total Orders
* Total Discount
* Total Freight
* Average Delivery Days
* Profit Proxy
* Active Products
* Discontinued Products
* Average Discount %

### 5. Dashboard Development

Designed a three-page interactive executive dashboard aligned with business decision needs.

---

## Dashboard Pages

### Page 1 — Sales & Revenue Overview

Focuses on:

* Revenue trends over time
* Order volume
* Employee sales performance
* Shipping delivery status

---

### Page 2 — Product & Category Intelligence

Focuses on:

* Top revenue-driving categories
* Discount impact on profit
* Active vs discontinued products

---

### Page 3 — Regional, Operational & People Performance

Focuses on:

* Top revenue markets by country
* Shipper cost vs delivery speed
* Employee contribution to revenue

---

## Data Model Preview

---

## Interactive Dashboard Walkthrough

A short dashboard demo video is available in:

`/project_demo/northwind_dashboard_walkthrough.mp4`

---

## Key Business Insights

* Revenue displays noticeable monthly fluctuations, indicating seasonal buying behavior.
* A few product categories contribute the majority of total revenue.
* Discounting improves sales penetration but weakens retained profitability.
* Certain countries dominate the organization’s total market contribution.
* Shipping providers differ significantly in both freight cost and delivery speed.
* Employee sales productivity is uneven, revealing top-performing contributors.

---

## Files Included

* `Northwind_Stage3_Dashboard.pbix`
* `Northwind_BI_Project_Report.pdf`
* `/screenshots.`
* `/project_demo`

---

## Dashboard Shareable Link

(https://app.powerbi.com/view?r=eyJrIjoiOWRjMGQ3MzItNzc2MC00YzMyLWJkODEtMmUxODRmMTk0ZTQ4IiwidCI6IjU2YjNjMjUzLTdlM2MtNDFjNC04NjEwLTc4YjIyYWNjN2E2MCJ9&pageName=4fd98775a21613d9ea76)

---

## Author

**Abigail Alabi**
Data Analyst | Business Intelligence Enthusiast | Turning raw data into decision-ready insights.

---
