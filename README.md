# 🛍️ Retail Sales Analysis (2010–2012)

## 🎯 Objective
To analyze historical store sales data using exploratory data analysis (EDA) techniques to identify key trends, assess economic factors, and provide actionable business insights to improve sales performance.

---

## 📁 Dataset Overview

The dataset consists of weekly sales data from multiple stores and departments over a three-year period. It includes:

- **Sales Data**: Weekly sales by store and department  
- **Features Data**: Economic factors such as fuel price, CPI, unemployment, and markdowns  
- **Store Metadata**: Store size and type information  

---

## 🧹 Data Cleaning

- Converted `Date` columns to datetime format  
- Merged all datasets using common keys (`Store`, `Date`, `IsHoliday`)  
- Handled missing values in `MarkDown1–5` by filling with 0  
- Applied `interpolate()` method for other null values  

---

## 📊 Exploratory Data Analysis (EDA)

### 🏬 Store-Level Insights
- Store Type A generated the most revenue overall  
- Larger stores tend to generate higher sales volumes  

### 📆 Holiday Effects
- Holiday weeks show slightly higher average sales  

### 🧾 Department Analysis
- Departments 92 and 95 recorded the highest total sales  
- Over 90 unique departments con
