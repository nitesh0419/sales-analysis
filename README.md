# 📊 Regional Sales Analysis & Business Insights

## 📌 Project Overview

This project analyzes a multi-sheet sales dataset to uncover **revenue trends, customer behavior, product performance, and profitability**.

It follows a complete data pipeline:
**Data Cleaning → Feature Engineering → Exploratory Data Analysis (EDA) → Business Insights**

---

## 🗂️ Data Sources

The dataset consists of multiple Excel sheets:

* Sales Orders
* Customers
* Products
* Regions
* State Regions
* 2017 Budgets

All datasets were merged into a single analytical dataset.

---

## 🧹 Data Preparation

* Merged datasets using keys like customer index, product index, and region id
* Removed redundant columns (`id`, `index`, etc.)
* Standardized column names
* Converted `order_date` to datetime format
* Exported final cleaned dataset → `final.csv`

---

## ⚙️ Feature Engineering

New features created:

* **Total Cost** = order_quantity × total_unit
* **Profit** = revenue − total_cost
* **Profit Margin (%)**
* **Order Month & Seasonality Features**

📌 Budget values were retained **only for 2017 data**

---

## 📊 Exploratory Data Analysis

### 📈 1. Monthly Sales Trend

* Continuous growth pattern with fluctuations
* Sales visualized in **millions for better readability**

---

### 🔁 2. Seasonality Analysis

* Monthly aggregation across all years
* Identifies peak and low-performing months

---

### 🏆 3. Top & Bottom Products

* Top 10 products contribute major share of revenue
* Bottom products show low performance → optimization opportunity

---

### 🛒 4. Sales by Channel

* Channels analyzed: Wholesale, Distributor, Export
* Distribution visualized using pie chart

---

### 💰 5. Order Value Distribution

* Histogram shows spread of order revenue
* Helps identify high-value vs low-value orders

---

### 📦 6. Unit Price Distribution

* Boxplots used for top products
* Detects pricing variation and outliers

---

### 🌍 7. Top States by Orders

* Identifies high-demand geographic regions
* Useful for logistics and expansion strategy

---

### 📊 8. Profitability by Channel

* Average profit margin differs across channels
* Helps identify most profitable sales channel

---

### 👥 9. Customer Analysis

* Top 10 customers → major revenue contributors
* Bottom 10 customers → low engagement

---

### 🎯 10. Customer Segmentation

* Bubble chart:

  * X → Revenue
  * Y → Profit Margin
  * Size → Number of Orders

👉 Helps identify:

* High-value customers
* High-margin customers

---

### 🔗 11. Correlation Analysis

* Strong relationship between:

  * Revenue & Profit
  * Cost & Revenue
* Visualized using heatmap

---

## 📈 Key Business Insights

* A small number of products generate most revenue
* Profit margins vary significantly by channel
* Certain states dominate order volume
* High-value customers drive a large portion of sales
* Seasonal trends impact revenue patterns

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📁 Output Files

* `final.csv` → cleaned dataset
* Multiple visualizations:

  * Line charts
  * Bar charts
  * Pie charts
  * Boxplots
  * Heatmaps

---

## 🚀 Future Scope

* Sales forecasting using Machine Learning
* Customer churn prediction
* Interactive dashboards (Power BI / Tableau)

---

## 👤 Author

Nitesh Sahani
