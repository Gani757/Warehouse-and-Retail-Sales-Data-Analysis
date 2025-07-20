# Warehouse-and-Retail-Sales-Data-Analysis
# 🏪 Warehouse & Retail Sales Analysis

An in-depth exploratory data analysis (EDA) of a retail and warehouse sales dataset, focusing on uncovering key sales trends across item types, months, and distribution channels.

---

## 📌 Objective

To analyze and visualize sales patterns using Python and identify high-performing products and sales trends across both warehouse and retail channels.

---

## 🧰 Technologies Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Jupyter Notebook**
- **Excel (for basic inspection)**
- **PDF Report Generation**

---

## 📊 Dataset Overview

The dataset includes:
- **Item Type** (category of product)
- **Retail Sales**
- **Warehouse Sales**
- **Retail Transfers**
- **Month, Year**
- Derived columns: `Total Sales`, `log_total_sales`, `date`

---

## 📈 Key Analyses

- Outlier detection and handling using IQR
- Created `Total Sales` as sum of retail and warehouse sales
- Removed negative/zero sales for cleaner analysis
- Sales distribution by:
  - Item Type
  - Month & Year (Time series)
  - Retail vs Warehouse
- Right-skewed data normalized using log transformation

---

## 📊 Visualizations Included

- Bar Plot: Sales by Item Type
- Pie Chart: Item Contribution to Total Sales
- Time Series Plot: Sales Over Time
- Distribution Plot: Before & After log transformation

---


