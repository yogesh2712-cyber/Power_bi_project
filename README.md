# 🍕 Pizza Sales Analysis Dashboard (Power BI)

## 📌 Project Overview
This project is an interactive **Pizza Sales Analysis Dashboard** created using **Microsoft Power BI**.  
The dashboard provides clear insights into sales performance, customer ordering behavior, revenue trends, and popular pizza categories and sizes.

It helps stakeholders understand **business performance**, identify **busiest days & times**, and make **data-driven decisions**.

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Microsoft Excel / CSV**
- **DAX (Data Analysis Expressions)**
- **Data Modeling & Visualization**

---

## 📂 Dataset Details
The dataset contains historical pizza sales data with the following key columns:

- `order_id`
- `order_date`
- `order_time`
- `pizza_name`
- `pizza_category`
- `pizza_size`
- `quantity`
- `unit_price`
- `total_price`

---

## 📊 Key KPIs in Dashboard
- **Total Revenue:** 817.86K  
- **Average Order Value:** 38.31  
- **Total Pizzas Sold:** 49.57K  
- **Total Orders:** 21.35K  
- **Average Pizzas per Order:** 2.32  

---

## 📈 Dashboard Insights
### 🔹 Sales Performance
- **Classic category** contributes the highest revenue and total orders.
- **Large size pizzas** generate maximum sales.

### 🔹 Time-Based Analysis
- Orders are **highest on weekends (Friday & Saturday evenings)**.
- Peak months include **July and January**.

### 🔹 Visuals Used
- KPI Cards
- Bar Charts
- Line Charts
- Donut Charts
- Slicers (Date & Category)
- Trend Analysis

---

## 🧮 DAX Measures Used
Some important DAX calculations:

```DAX
Total Revenue = SUM(pizza_sales[total_price])

Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

Total Pizza Sold = SUM(pizza_sales[quantity])

Avg Order Value = 
DIVIDE([Total Revenue], [Total Orders])

Avg Pizza Per Order = 
DIVIDE([Total Pizza Sold], [Total Orders])
🖼 Dashboard Preview

🚀 How to Use
Download or clone the repository

Open the .pbix file using Power BI Desktop

Interact with slicers to explore insights

Customize or extend the dashboard as needed

📌 Business Use Case
Sales performance monitoring

Customer purchasing behavior analysis

Identifying high-revenue products

Improving inventory & marketing strategies
