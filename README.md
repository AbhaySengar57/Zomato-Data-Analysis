# 🍽️ Zomato Bangalore Restaurant Data Analysis

A comprehensive data analysis project exploring Zomato restaurant listings in Bangalore using Python (Pandas, Seaborn, Matplotlib). This project uncovers business insights like popular cuisines, restaurant types, cost distributions, and service offerings like online ordering.

---

## 📊 Project Overview

- 📍 **Dataset:** Zomato restaurant data for Bangalore
- 🧰 **Tools Used:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook
- 📈 **Skills Applied:** Data Cleaning, EDA, Visualization, Feature Engineering

---

## 🧹 Data Cleaning Tasks

- Removed unwanted columns like `url`, `phone`, `address`
- Converted `rate` and `cost` columns to numeric format
- Handled missing values and inconsistent entries
- Dropped duplicate rows

---

## 🔍 Exploratory Data Analysis (EDA)

### 📍 Top 10 Locations with the Most Restaurants
- BTM, Indiranagar, and Koramangala top the list.

### 📦 Online Ordering Trend
-Count of restaurants offer online ordering.

### 📅 Table Booking Availability
- Only a smaller percentage allow table reservations.

### 🍽️ Most Common Restaurant Types
- Quick Bites and Casual Dining dominate the market.

### 🍲 Top 10 Cuisines
- North Indian, Chinese, and South Indian are the most offered cuisines.

### 💰 Cost Distribution
- Most restaurants fall in the ₹200–₹600 for two people range.


---

## 📉 Visualizations Used

| Chart Type      | Purpose                          |
|-----------------|----------------------------------|
| Bar Chart       | Top Locations, Cuisines, Types   |
| Pie Chart       | Online Order, Table Booking      |
| Histogram       | Cost for Two Distribution        |
| Countplot       | Online ordering, Table Booking   |      

All visualizations were created using `matplotlib` and `seaborn`.

---

## 📁 File Structure

Zomato-Data-Analysis/
├── cleaned_zomato.csv
├── Zomato_EDA_analysis.ipynb
└── README.md

---
## 💡 Key Learnings

- Data preprocessing (missing values, transformation)
- Visual storytelling with Python
- Extracting actionable business insights from real-world data

---
! Full dataset is too large. A sample of 1,000 rows is included for quick reference.
