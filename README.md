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

**📸 Add your data model screenshot below.**

`![Power BI Data Model](screenshots/data-model.png)`

## 📈 Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of sales, gross profit, gross margin, orders, units sold, average order value, and target attainment.

**📸 Add Executive Overview screenshot below.**

`![Executive Overview](screenshots/01-executive-overview.png)`

### 2. Sales Performance & Targets
Analyzes sales trends, regional performance, sales channels, order status, and actual sales compared with targets.

**📸 Add Sales Performance & Targets screenshot below.**

`![Sales Performance and Targets](screenshots/02-sales-performance-targets.png)`

### 3. Product & Category Analysis
Evaluates product and category performance, subcategory sales, profitability, and factors associated with product categories.

**📸 Add Product & Category Analysis screenshot below.**

`![Product and Category Analysis](screenshots/03-product-category-analysis.png)`

### 4. Customer Insights
Explores customer segments, customer sales contribution, purchasing behavior, and customer-level performance.

**📸 Add Customer Insights screenshot below.**

`![Customer Insights](screenshots/04-customer-insights.png)`

### 5. Sales Team Performance
Analyzes employee sales performance, profitability, and individual contributions to business results.

**📸 Add Sales Team Performance screenshot below.**

`![Sales Team Performance](screenshots/05-sales-team-performance.png)`

### 6. Returns & Operations
Examines product returns and operational indicators to identify return patterns and areas requiring attention.

**📸 Add Returns & Operations screenshot below.**

`![Returns and Operations](screenshots/06-returns-operations.png)`

### 7. Order Details
Provides detailed order-level information for reviewing transactions and investigating sales records.

**📸 Add Order Details screenshot below.**

`![Order Details](screenshots/07-order-details.png)`

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

**📸 Optional: Add a screenshot of the Region Tooltip here.**

`![Region Tooltip](screenshots/region-tooltip.png)`

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
**Sravanti**  
B.Tech – Computer Science and Engineering (AI & ML), 2026

**Skills:** Power BI | DAX | Power Query | Microsoft Excel | SQL | Data Analytics

---

*This project uses fictional retail data for learning and portfolio demonstration purposes.*
