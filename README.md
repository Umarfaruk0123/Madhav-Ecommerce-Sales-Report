
# 🛍️ Madhav Ecommerce Sales Dashboard — Power BI Project

An interactive ecommerce sales analytics dashboard built using **Power BI**. The project analyzes sales, profit, quantity, and customer data across Indian states using two relational datasets.

---


![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white) 
![GoogleSheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the badge&logo=googlesheets&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=database&logoColor=white) 
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) 
![EDA](https://img.shields.io/badge/Project-EDA-3670A0?style=for-the-badge) 
![KPI Analysis](https://img.shields.io/badge/Project-KPI%20Analysis-0078D4?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) 
![Dashboard](https://img.shields.io/badge/Project-Dashboard-F2C811?style=for-the-badge) 


---


## 📁 Project Structure

```
Madhav-Ecommerce-Sales-Dashboard/
│
├── Orders.csv                                  # Customer & order location data (500 records)
├── Details.csv                                 # Order financial & product details (1500 records)
├── Dashboard_1_madhev_ecommerce_sales.pbix     # Power BI dashboard file
└── README.md                                   # Project documentation
```

---

## 📊 Dataset Overview

### 📄 Orders.csv — 500 records | 5 columns

| Column | Description |
|--------|-------------|
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| CustomerName | Name of the customer |
| State | Delivery state (19 states) |
| City | Delivery city (25 cities) |

### 📄 Details.csv — 1,500 records | 7 columns

| Column | Description |
|--------|-------------|
| Order ID | Links to Orders.csv |
| Amount | Revenue from the order |
| Profit | Profit earned |
| Quantity | Units ordered |
| Category | Electronics / Furniture / Clothing |
| Sub-Category | 17 sub-categories (Phones, Chairs, Saree, etc.) |
| PaymentMode | COD / EMI / UPI / Credit Card / Debit Card |

---

## 📈 Dashboard Highlights

- 💰 **KPI Cards** — Total Sales Amount, Total Profit, Total Quantity, Average Order Value
- 📅 **Profit by Month** — Monthly profit trend across the year
- 🗺️ **Sales by State** — Top performing states across India
- 👥 **Sales by Customer** — Top customers by purchase amount
- 🏷️ **Sales by Category & Sub-Category** — Product-level performance breakdown
- 💳 **Sales by Payment Mode** — COD vs UPI vs EMI vs Cards split
- 📦 **Quantity by Category** — Volume distribution across Electronics, Furniture & Clothing
- 🔍 **Interactive Filters** — Slicers for Quarter and State

---

## 🔍 Key Insights

- 👗 **Clothing** contributes the highest quantity of orders
- 📱 **Electronics** drives the most revenue
- 💵 **COD** is the most preferred payment mode
- 🏆 **Maharashtra** and **Madhya Pradesh** are top states by sales
- 📉 Certain months show negative profit — indicating returns or high discounts

---

## 🛠️ Tools & Features Used

- **Power BI Desktop**
- Data Modeling (relationship between Orders & Details via Order ID)
- Power Query for data cleaning & transformation
- DAX Measures (Total Sales, Total Profit, AOV, Profit %)
- Bar Charts, Donut Charts, Line Charts, Map Visual
- KPI Cards & Slicers

---

## 🚀 How to Use

1. Download all files from this repository
2. Open `Dashboard_1_madhev_ecommerce_sales.pbix` in **Power BI Desktop**
3. If prompted, re-link the data sources to your local `Orders.csv` and `Details.csv`
4. Use the **Quarter** and **State** slicers to explore the data interactively

---

## 👤 Author

> **[Your Name]**
>
> 🔗 [LinkedIn](https://www.linkedin.com/in/umarfaruk-shaikh/) | 🐙 [GitHub](https://github.com/Umarfaruk0123)

---

⭐ If you found this project helpful, give it a star!
