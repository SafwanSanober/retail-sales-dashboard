# 📊 Retail Sales Performance Dashboard Power BI

An interactive Power BI dashboard providing a comprehensive analysis of retail sales data — tracking total revenue, orders, quantity, monthly trends, customer-wise performance, and country-wise distribution.

## 🎯 Features
- **KPI Cards** — Total Revenue, Total Orders, and Total Quantity at a glance
- **Revenue by Year** — Donut chart comparing performance across 2001–2003
- **Revenue by Month** — Bar chart showing monthly sales trends
- **Revenue by CustomerID** — Treemap visualizing top customer contributions
- **Revenue by Country** — World map showing geographic revenue distribution
- **Revenue by Name** — World map showing customer-wise distribution
- **Interactive Filters** — Slice the dashboard by Month, Country, and City
- **Detailed Data Table** — CustomerID, AccountNumber, ContactFirstName, and more

## 🖼️ Preview

![Dashboard Overview](screenshots/overview.png)

## 🛠️ Built With
- Power BI Desktop
- DAX (calculated measures)
- Power Query (data transformation & cleaning)

## 🚀 How to View
1. Clone this repository:
git clone https://github.com/SafwanSanober/retail-sales-dashboard.git
2. Open the `.pbix` file in Power BI Desktop

## 📈 Key Insights
- Total revenue reached **43.44M** across **5,199 orders**
- A total of **76K units** were sold
- **2003** accounted for the majority of revenue (**70.6%**, ~30.67M), showing strong year-over-year growth from 2001
- **August and September** show peak sales activity in the monthly trend
- Revenue distribution across customers and countries indicates a globally spread customer base, with certain regions showing higher concentration

## 📁 Data Source
Raw data is available in the `data/` folder (`Retail.xlsx`).
