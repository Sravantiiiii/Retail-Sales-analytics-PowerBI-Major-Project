# 📊 Retail Sales Analytics | Power BI Major Project

## 📌 Project Overview
The **Retail Sales Analytics** project is an end-to-end Power BI solution designed to analyze retail sales performance, profitability, customer behavior, employee performance, and returns. It transforms raw retail data into interactive dashboards that help users monitor KPIs and make data-driven business decisions.

## 🎯 Project Objectives
- Analyze sales performance across regions, categories, and channels.
- Compare actual sales with revenue targets.
- Evaluate product profitability and gross margins.
- Understand customer purchasing patterns and repeat purchases.
- Analyze employee sales performance.
- Monitor returns and operational performance.
- Provide detailed order-level insights.

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures, KPIs, and time intelligence
- **Data Modeling** – Relationships between fact and dimension tables
- **Microsoft Excel / CSV** – Source data

## 📂 Project Dataset
The project uses fictional retail data covering **January 2023 to December 2025**.

| Dataset | Records |
|---|---:|
| Customers | 1,500 |
| Products | 120 |
| Employees | 45 |
| Orders | 12,000 |
| Order Items | 28,641 |
| Sales Targets | 1,620 |
| Returns | 1,239 |

## 🔄 Data Preparation
Data preparation was performed using Power Query:
- Checked data quality and handled duplicates and missing values.
- Corrected data types and formatting.
- Cleaned inconsistent text values.
- Checked date fields and numerical values.
- Prepared tables for data modeling and analysis.

## 🧩 Data Model
The data model connects customers, products, employees, orders, order items, sales targets, returns, and the calendar table to support interactive analysis.


<img width="437" height="381" alt="DataModel" src="https://github.com/user-attachments/assets/acbc3c60-c0ce-4e24-9dbb-58e4a20eaf45" />


## 📈 Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of sales, gross profit, gross margin, orders, units sold, average order value, and target attainment.

<img width="700" height="392" alt="Executive_overview" src="https://github.com/user-attachments/assets/0bb4944c-c559-45ba-94a9-8a50511f0c4e" />


### 2. Sales Performance & Targets
Analyzes sales trends, regional performance, sales channels, order status, and actual sales compared with targets.

<img width="710" height="398" alt="Sales_Performance Target" src="https://github.com/user-attachments/assets/9b8973e4-c00b-4d4d-b749-618f9c21cc7b" />


### 3. Product & Category Analysis
Evaluates product and category performance, subcategory sales, profitability, and factors associated with product categories.

<img width="709" height="397" alt="Product Category_Analysis" src="https://github.com/user-attachments/assets/154a8b5f-6c4e-471d-8af4-5bea0299be9d" />


### 4. Customer Insights
Explores customer segments, customer sales contribution, purchasing behavior, and customer-level performance.

<img width="709" height="398" alt="Customer_Insights" src="https://github.com/user-attachments/assets/051861c8-0284-468d-831e-f489f2166a6d" />


### 5. Sales Team Performance
Analyzes employee sales performance, profitability, and individual contributions to business results.

<img width="707" height="398" alt="Sales_Team_performance" src="https://github.com/user-attachments/assets/90653e8e-f120-41c1-8d9e-68721e07b521" />


### 6. Returns & Operations
Examines product returns and operational indicators to identify return patterns and areas requiring attention.

<img width="709" height="399" alt="Returns Operations" src="https://github.com/user-attachments/assets/2fedf118-5b1f-48a3-8727-f17d8f14d46e" />


### 7. Order Details
Provides detailed order-level information for reviewing transactions and investigating sales records.

<img width="710" height="399" alt="Order_Details" src="https://github.com/user-attachments/assets/c8ac2031-04f5-4204-afaf-9d28785f0564" />


## 📐 Key Performance Indicators (KPIs)
- Net Sales
- Gross Sales
- Gross Profit
- Gross Margin %
- Total Orders
- Units Sold
- Average Order Value
- Revenue Target
- Target Attainment %
- Return Rate

## 🧮 DAX & Analytical Features
- Sales, profit, margin, and order calculations.
- Month-over-month and year-over-year comparisons.
- Time intelligence and year-to-date analysis.
- Target variance and target attainment.
- Product profitability and customer repeat-purchase analysis.
- Employee performance rankings and return-rate calculations.

## 🖱️ Interactivity & Navigation
- Interactive slicers and filters.
- Drill-down and drill-through analysis.
- Bookmarks and navigation buttons.
- Reset Filters functionality.
- Custom report page tooltips for contextual information on hover.

## 🔍 Report Page Tooltip
A dedicated **Region Tooltip** report page provides additional regional sales information when users hover over the Sales by Region visual, improving dashboard interactivity without navigating away from the main report.

<img width="299" height="221" alt="Region_ToolTip" src="https://github.com/user-attachments/assets/eb21e9d2-a9b2-4270-90bc-9e71613bb6e0" />


## ✅ Validation & Quality Checks
- Checked dimension key uniqueness and data types.
- Reviewed blanks, duplicates, and date ranges.
- Reconciled key measures against source data.
- Validated order counts using distinct order IDs.
- Tested target calculations and report interactivity.

## 📦 Project Deliverables
- Power BI report (`.pbix`)
- Data model screenshot
- Measure dictionary
- Validation checklist
- Project summary and report screenshots

## 💡 Business Value
This project demonstrates how Power BI can convert raw retail data into meaningful business insights, support KPI monitoring, compare performance against targets, and help stakeholders investigate sales, customer, product, employee, and operational trends.

## 👩‍💻 Author
**Sravanti Kondala**  

**Skills:** Power BI | DAX | Power Query | Microsoft Excel | SQL | Data Analytics

---

*This project uses fictional retail data for learning and portfolio demonstration purposes.*
