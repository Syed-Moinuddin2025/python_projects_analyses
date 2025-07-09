# 🍕 Pizza Sales Analysis (Python Project)

<p align="center">
  <img src="https://github.com/Syed-Moinuddin2025/python_projects_analyses/blob/main/05_Pizza_Sales_Analysis/Images/pizza.png?raw=true" alt="Pizza Sales Project" width="700">
</p>


This project analyzes pizza sales data using Python with pandas, matplotlib, seaborn, and Plotly. We derive business KPIs, sales insights, and powerful visualizations from raw CSV data.

---

## 📁 Dataset

Single cleaned CSV file used:
- `pizza_sales.csv` with the following columns:
  - `pizza_id`, `order_id`, `pizza_name_id`, `quantity`, `order_date`, `order_time`
  - `unit_price`, `total_price`, `pizza_size`, `pizza_category`, `pizza_ingredients`, `pizza_name`

---

## 🎯 Business Questions Answered

### A. 📊 KPIs

1️⃣ **Q1. What is the total revenue generated?**  
2️⃣ **Q2. What is the average order value?**  
3️⃣ **Q3. How many pizzas were sold in total?**  
4️⃣ **Q4. How many total orders were placed?**  
5️⃣ **Q5. What is the average number of pizzas per order?**

---

### B. 📈 Trend & Category Analysis

6️⃣ **Q6. What is the daily trend of total orders?**  
7️⃣ **Q7. What is the hourly distribution of orders?**  
8️⃣ **Q8. What % of total sales comes from each pizza category?**  
9️⃣ **Q9. What % of total sales comes from each pizza size?**  
🔟 **Q10. How many pizzas were sold by each category?**

---

### C. 🏆 Best & Worst Sellers

1️⃣1️⃣ **Q11. Who are the top 5 best-selling pizzas by quantity sold?**  
1️⃣2️⃣ **Q12. Who are the bottom 5 worst-selling pizzas?**

---

## 📊 Tools & Libraries Used

- **Python** 🐍
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for basic plots
- `plotly.express` for interactive visuals
- `jupyter notebook` for presentation

---

## 📂 Project Structure

05__Pizza_Sales_Project_Python/
----------------------------
├── pizza_sales.csv
--------------------------
├── Pizza_Sales_Analysis.ipynb
----------------------------------------
├── Images/ (charts saved here, optional)
---------------------------------
└── README.md
---

---

## ✅ Highlights

- Data cleaning: Converted `order_date` and `order_time` properly using `pd.to_datetime()`
- Created `order_hour` for hourly analysis
- Used `groupby()` + Plotly for interactive charts
- Organized KPIs with questions on top of each analysis cell

---

## 📌 Sample Visualization

> Hourly Orders Chart – Plotly Line Chart

---

## ✅ Highlights

- Data cleaning: Converted `order_date` and `order_time` properly using `pd.to_datetime()`
- Created `order_hour` for hourly analysis
- Used `groupby()` + Plotly for interactive charts
- Organized KPIs with questions on top of each analysis cell

---

## 📌 Sample Visualization

> Hourly Orders Chart – Plotly Line Chart

```
python
df['order_hour'] = pd.to_datetime(df['order_time'].astype(str), format='%H:%M:%S', errors='coerce').dt.hour
hourly_orders = df.groupby('order_hour')['order_id'].nunique().reset_index()
fig = px.line(hourly_orders, x='order_hour', y='order_id', title='Hourly Orders')
fig.show()

```
 
 🙌 Author
Syed Moinuddin
🔗 GitHub Profile
