# 🛒 Freshco Hypermarket Analysis – Excel Capstone Project

## 📌 Project Overview
This Excel-based capstone project analyzes operational and customer data from Freshco Hypermarket to derive insights into:

- Order Completion Rates
- Customer Behavior
- Delivery Performance (Arrival to Pickup, Pickup to Delivery)

## 🎯 Objectives
- Evaluate Freshco’s order fulfillment efficiency
- Identify trends in customer activity
- Analyze delivery timelines and detect SLA breaches

## 🧾 Data Sources
The project includes the following datasets (synthetic data created for academic use):
- `orders.xlsx` – Order information including dates, status, and delivery type
- `customers.xlsx` – Customer demographics and activity
- `delivery_details.xlsx` – Timestamps for each delivery stage

## 📊 Key Metrics & Insights
- **Completion Rate:** Percentage of orders successfully completed
- **Customer Analysis:** Region-wise distribution, frequency of orders, repeat customers
- **Delivery Timings:**
  - Arrival to Pickup (Warehouse Handling Time)
  - Pickup to Delivery (Transit Time)

## 📈 Features
- Interactive dashboards using PivotTables & Slicers
- Visualizations including bar charts, pie charts, and trend lines
- Use of formulas (e.g., `DATEDIF`, `AVERAGEIFS`, `COUNTIF`)
- Conditional formatting to flag delays

## 💻 Tools Used
- Microsoft Excel
- Power Query (for data cleaning)
- Power Pivot (optional for advanced aggregation)
- Excel Charts & Slicers

## 📁 Repository Structure
```bash
Freshco-Hypermarket-Excel-Project/
│
├── data/
│   ├── orders.xlsx
│   ├── customers.xlsx
│   └── delivery_details.xlsx
│
├── dashboards/
│   └── Freshco_Dashboard.xlsx
│
├── README.md
└── summary.pdf (optional executive report)

