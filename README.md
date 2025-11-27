# 🍕 Pizza Sales Analysis

## 📌 Project Overview
The **Pizza Sales Analysis** project provides a complete analytical study of a pizza store’s transactional dataset. It uncovers important KPIs, trends, and insights to support decision-making in sales, marketing, and operations.

## 🎯 Business Objectives
- Calculate **Total Revenue**, **Total Pizzas Sold**, and **Total Orders**
- Analyse **sales distribution** by category, size, and type
- Identify **top and bottom** performing pizzas
- Understand **daily, hourly, monthly** sales trends
- Compute **AOV (Average Order Value)** and **Average Pizzas per Order**
- Provide interactive **visual dashboards** for management

## 📂 Dataset Description
**Dataset:** `pizza_sales.csv`

**Key fields include:**
- `order_id`
- `pizza_id`
- `pizza_name`
- `quantity`
- `total_price`
- `date`, `time`
- `pizza_category`, `pizza_size`

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue** = Sum of total_price
- **Total Pizzas Sold** = Sum of quantity
- **Total Orders** = Count of unique order_id
- **AOV (Average Order Value)** = Total Revenue ÷ Total Orders
- **Average Pizza per Order** = Total Pizzas Sold ÷ Total Orders

## 📈 Analysis & Visualizations
### 🗓️ Daily Trend
Sales by day of the week to support staffing and planning.

### 🕒 Hourly Trend
Identifies peak buying hours and supports operational decisions.

### 📅 Monthly Trend
Shows monthly seasonality patterns and revenue growth.

### 🍕 Sales by Category
Revenue and quantity breakdown across pizza categories.

### 📏 Sales by Pizza Size
Comparison of revenues from S, M, L, XL sizes — Large pizzas typically dominate revenue.

### 🏆 Top 5 Best-Selling Pizzas
Used for promotions and menu strategy.

### 🛑 Bottom 5 Least-Selling Pizzas
Helps in deciding which pizzas may require redesign or removal.

### Business Questions Answered
- What is the total revenue generated?

  `$817,860.05`
  
- How many pizzas were sold in total?

`49,574.00`

- Which category and size of pizzas perform best?

  `Chicken-L & Vegie-L`
  
- Which pizzas are the top and bottom performers?

`5 Best-Selling Pizzas: The Thai Chicken Pizza, The Barbecue Chicken Pizza, The California Chicken Pizza, The Classic Deluxe Pizza &The Spicy Italian Pizza`

` 5 Least-Selling Pizzas : The Spinach Pesto Pizza, The Mediterranean Pizza, The Spinach Supreme Pizza, The Green Garden Pizza & The Brie Carre Pizza`



- What is the average order value and average pizzas per order?

  `$2.32`
  
- What are the sales trends by day, month, and time of day?
  `Sales trends reveal clear seasonality and time-based patterns. Orders show a steady increase during peak periods across days, months, and hours of the day. These patterns help identify busy periods and support operational planning.`


## 📁 Deliverables
- Visualizations
- BRD
- Insights report

## 🚀 Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Jupyter Notebook

## 📝 Conclusion & Recommendations
The project helps management to:
- Promote high-performing pizza categories
- Optimize the menu by evaluating low sellers
- Plan inventory and staffing through trend analysis
- Track KPIs using dashboards for continuous improvement
