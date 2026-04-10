# 🛒 Maven Market Retail Analytics (Power BI)

## 🎯 Project Objective

To analyze retail business performance using Power BI and build an interactive dashboard for tracking sales, profit, orders, customers, and returns.

---

## 📂 Dataset

* MavenMarket_Transactions_1997.csv
* MavenMarket_Transactions_1998.csv
* MavenMarket_Calendar.csv
* MavenMarket_Customers.csv
* MavenMarket_Products.csv
* MavenMarket_Regions.csv
* MavenMarket_Returns_1997-1998.csv
* MavenMarket_Stores.csv

---

## 🛠 Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Power Query (M Language)

---

## ⚙️ Data Preparation

* Combined transaction files using Power Query (Append)
* Cleaned and transformed datasets
* Created relationships between tables
* Built a star schema data model

---

## 📊 Data Model

**Fact Tables**

* Transaction_Data
* Return_Data

**Dimension Tables**

* Calendar
* Customers
* Products
* Stores
* Regions

---

## 📈 Key Measures

* Total Revenue
* Total Cost
* Total Profit
* Total Orders
* Total Quantity Sold
* Total Returns
* Profit Margin %
* Average Order Value
* Revenue YoY %
* Rolling Revenue (7D, 30D, 90D)
* Target vs Actual Metrics

---

## 📊 Dashboard Pages

* Executive Dashboard
* Map Analysis
* Region Detail
* Store Detail
* Customer Detail

---

## 🗂 Repository Structure

```text
maven-market-retail-analytics/

├─ assets/
│  ├─ icons/
│  ├─ logo/
│  └─ screenshots/

├─ data/
│  ├─ Transactions/
│  │  ├─ MavenMarket_Transactions_1997.csv
│  │  └─ MavenMarket_Transactions_1998.csv
│  ├─ MavenMarket_Calendar.csv
│  ├─ MavenMarket_Customers.csv
│  ├─ MavenMarket_Products.csv
│  ├─ MavenMarket_Regions.csv
│  ├─ MavenMarket_Returns_1997-1998.csv
│  └─ MavenMarket_Stores.csv

├─ pbix/
│  └─ maven-market-retail-analytics.pbix

└─ docs/
   └─ model-diagram.png
```

---

## 🚀 How to Use

1. Download the PBIX file
2. Open in Power BI Desktop
3. Explore dashboard pages

---

## 📌 Key Insights

* Sales and profit trends over time
* Top-performing products and regions
* Customer behavior and purchasing patterns
* Impact of returns on revenue

---

## 👤 Author

**Niraj Nishar**

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
