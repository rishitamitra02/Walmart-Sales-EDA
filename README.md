# Walmart-Sales-EDA
Exploratory Data Analysis of Walmart weekly sales data using Python to identify store performance, sales trends, holiday impact, and key business insights.
# Walmart Sales Data Analysis 📊

## 📌 Project Overview
This project focuses on **exploratory data analysis (EDA)** of Walmart sales data to understand
sales patterns across stores, time, and holidays.  
The objective is to derive **business insights** that can help in decision-making related to
store performance, seasonality, and demand fluctuations.

---

## 🎯 Objectives
- Analyze total sales performance across different Walmart stores
- Identify weekly sales trends over time
- Compare sales behavior during **holiday vs non-holiday periods**
- Detect outliers in weekly sales
- Examine correlations among numerical variables

---

## 🗂 Dataset Description
The dataset contains weekly sales data for multiple Walmart stores.

**Key Features:**
- `Store` – Store ID  
- `Date` – Week of sales  
- `Weekly_Sales` – Sales for the given week  
- `Holiday_Flag` – 1 indicates holiday week, 0 indicates non-holiday  
- Other numerical features such as temperature, fuel price, CPI, unemployment

---

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook**

---

## 🔍 Data Cleaning & Preparation
- Checked dataset shape, data types, and missing values
- Converted `Date` column to datetime format
- Checked for duplicate records
- Generated descriptive statistics
- Identified outliers using **IQR method**

---

## 📊 Exploratory Data Analysis & Visualizations

### 1. Total Sales by Store
- Aggregated weekly sales by store
- Identified top-performing and low-performing stores

📁 File: `Total Sales By Stores.png`

---

### 2. Weekly Sales Trend Over Time
- Analyzed overall sales trend across weeks
- Identified seasonality and demand fluctuations

📁 File: `Weekly Sales Trend Over.png`

---

### 3. Holiday vs Non-Holiday Sales Analysis
- Compared weekly sales during holidays and non-holidays
- Observed higher sales volatility during holiday periods

📁 File: `Holiday vs Non-Holiday Weekly Sales.png`

---

### 4. Correlation Analysis
- Studied relationships between numerical variables
- Visualized correlations using a heatmap

📁 File: `Correlation Heatmap of Numerical Features.png`

---

## 📈 Key Insights
- Some stores contribute disproportionately to total sales
- Clear sales fluctuations observed over time
- Holiday weeks generally show higher sales variation
- Weak to moderate correlations exist between sales and economic factors

---

## 📁 Repository Structure
