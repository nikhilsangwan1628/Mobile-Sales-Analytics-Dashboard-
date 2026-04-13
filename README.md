#  Mobile Sales Analytics Dashboard – Power BI

📖 Overview

This Power BI dashboard provides an end-to-end analysis of **mobile phone sales performance**. It enables business stakeholders to monitor key sales metrics, track month-to-date progress, and compare current performance against the same period last year — all through interactive, filterable visuals.

The report is built on two core datasets: "Sales_data" and a "Custom_Calendar" table, enabling robust time intelligence across the dashboard.

---

📊 Report Pages

1. 🏠 Dashboard (Main Overview)
A high-level snapshot of overall sales performance, featuring:
- KPI Cards – Total Sales, Total Transactions, Total Quantity Sold, Average Price
- Line Chart – Monthly quantity trend
- Area Chart – Total sales by day of the week
- Clustered Bar Chart – Top-selling mobile models by revenue
- Pie Chart – Transactions breakdown by payment method
- Funnel Chart – Customer ratings by rating status
- Table – Brand-wise sales and transaction summary
- Map Visual – City-level sales distribution
- Slicers – Filter by Mobile Model, Payment Method, and Brand

2. 📅 MTD Report (Month-To-Date)
Tracks sales progress within the current month:
- KPI Cards – MTD Total Sales, Transactions, Quantity, Average Price
- Line Chart – Day-by-day comparison of Total Sales vs. MTD Sales
- Slicers – Filter by Mobile Model, Payment Method, and Date Hierarchy (Year / Quarter / Month / Day)

3. 📆 Same Period Last Year Report
Year-over-year performance comparison:
- KPI Cards – Sales, Transactions, Quantity, Average Price
- Clustered Column Charts – Total Sales vs. Same Period Last Year, broken down by Quarter, Year, and Month
- Table – Yearly and quarterly comparison of current vs. prior year sales
- Slicers – Filter by Mobile Model, Payment Method, and full Date Hierarchy

---

🔑 Key Metrics

| Metric | Description |
|---|---|
| "Total_Sales" | Overall revenue generated |
| "Transaction" | Number of sales transactions |
| "Total_Quantity" | Units sold |
| "Average Price" | Average selling price per unit |
| "MTD" | Month-to-date cumulative sales |
| "Same Period Last Year" | Prior year sales for the equivalent time window |

---

🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX** – For time intelligence measures (MTD, SPLY)
- **Custom Calendar Table** – For advanced date filtering and hierarchy
- **Data Source:** Mobile sales transaction data

---



