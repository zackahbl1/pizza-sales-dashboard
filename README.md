# 🍕 Pizza Sales Dashboard – SQL + Power BI

## 📌 Project Overview

This project analyzes pizza sales data using SQL for KPI validation and Power BI for dashboard creation.  
It offers insights into revenue, order patterns, product category performance, and sales trends, helping decision-makers optimize marketing, inventory, and menu offerings.

## 📂 Dataset

- **File:** `pizza_sales.csv`  
- **Description:** Transaction-level pizza sales data with order details, product information, and pricing.  
- **Source:** Provided as part of the project exercise.

### Dataset Features

| Column Name       | Description                                      |
|-------------------|------------------------------------------------|
| pizza_id          | Unique identifier for each pizza sold           |
| order_id          | Unique identifier for each customer order       |
| pizza_name_id     | Identifier linking pizza name to its details    |
| quantity          | Number of units sold for that pizza in the order|
| order_date        | Date when the order was placed                   |
| order_time        | Time when the order was placed                   |
| unit_price        | Price per unit of the pizza                       |
| total_price       | Total price for the pizza(s) in that order line |
| pizza_size        | Size of the pizza (Small, Medium, Large, etc.)  |
| pizza_category    | Category of the pizza (e.g., Classic, Supreme)  |
| pizza_ingredients | Ingredients used in the pizza                     |
| pizza_name        | Full name of the pizza                            |

## 📊 Key Performance Indicators (KPIs)

| Metric                 | Value   |
|------------------------|---------|
| Total Revenue          | 817.86K |
| Average Order Value    | 38.31   |
| Total Pizzas Sold      | 49,574  |
| Total Orders           | 21,350  |
| Average Pizzas Per Order | 2.32  |

## 📅 Insights from the Dashboard

### Daily Trends
- Orders peak on weekends, especially Friday and Saturday evenings.

### Monthly Trends
- Highest orders occur in July and January.

### Category Performance
- Classic category contributes the most sales and total orders.

### Size Performance
- Large size pizzas generate the maximum sales.

### Product Performance
- **Top Revenue:** Thai Chicken Pizza  
- **Top Orders:** Classic Deluxe Pizza  
- **Lowest Revenue & Orders:** Brie Carre Pizza  

## 🛠 Tools & Technologies Used

- SQL – KPI calculation and data validation  
- Power BI – Data visualization and dashboard creation  
- CSV Dataset – `pizza_sales.csv`  

## 🚀 How to Use

1. Import `pizza_sales.csv` into your SQL database (MySQL, SQL Server, etc.).  
2. Run the SQL queries in `/queries` to validate KPIs.  
3. Open the `.pbix` file in Power BI Desktop.  
4. Connect Power BI to the dataset or database for interactive visuals.

## 📈 Business Value

This dashboard enables:  
- **Performance tracking:** Monitor sales, orders, and product performance.  
- **Decision making:** Identify high-performing categories and underperforming products.  
- **Trend analysis:** Plan marketing and inventory for peak sales periods.

## 🔧 Ways to Improve

- **Add Customer Demographics:** Incorporate customer age, location, or preferences to personalize marketing strategies.  
- **Enhance Time Analysis:** Include hourly trends or heatmaps for more granular insight into peak order times.  
- **Introduce Forecasting Models:** Use time series analysis or machine learning to predict future sales trends.  
- **Integrate Inventory Data:** Link sales with inventory to manage stock levels and reduce waste.  
- **Mobile-friendly Dashboard:** Optimize Power BI visuals for mobile devices for better accessibility.  
- **Add More Visualizations:** Include heatmaps, scatter plots, or geographic maps to reveal additional insights.  
- **Automate Data Refresh:** Schedule automatic data updates for real-time or near real-time dashboard accuracy.  
- **Include Customer Feedback:** Analyze reviews or ratings to connect sales performance with customer satisfaction.



