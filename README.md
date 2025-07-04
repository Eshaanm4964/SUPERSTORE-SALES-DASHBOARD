# SUPERSTORE-SALES-DASHBOARD

# 🛒 Superstore Sales Dashboard - Power BI Project

## 📊 Overview

This Power BI report provides an interactive analysis of **Superstore sales data** across various dimensions such as **Region**, **Category**, **Segment**, and **City** over the years **2014 to 2017**.

The dashboard is split into **two pages**:
- **Main Dashboard** (Performance KPIs, Sales Trends, and Regional/Category Insights)
- **Insights Page** (Top 10 insights with supporting visuals)

## 🖥️ Features

### ✅ Page 1: **Superstore Sales Dashboard**
- **Key KPIs**: Total Products, Sales, Profit, Avg. Discount, Avg. Profit Margin
- **Filters**: Region, Category, Customer ID, and Year
- **Visuals**:
  - Line Chart: Sales Trend by Year
  - Table: Region-wise Profit & Margin by Year
  - Bar Charts:
    - Sales by Category
    - Sales by Region
    - Order Count by City
  - Donut Chart: Profit Margin by Segment

🔔 **Interactive Bulb Icon (Top-Right)**:
- Clicking the 💡 icon takes you to the **Insights page**.

### ✅ Page 2: **Top 10 Insights**
- Dynamic bullet list of **top business insights** derived from the main dashboard
- Supporting visuals:
  - Sales and Discount by Region
  - Max Sales by City (per Category and Segment)
  - Sales vs. Profit pie chart
- Insights are organized with emojis and bold highlights for easy reading

## 💡 Navigation Setup (Using the Bulb Button)

To implement navigation between pages in Power BI Desktop:

1. Select the **bulb icon button** on the Main page.
2. In the **Visualizations pane**:
   - Set **Action** = `On`
   - Set **Type** = `Page navigation`
   - Set **Destination** = `Insights` (or the name of Page 2)

✅ Clicking the bulb in View Mode takes users directly to the Insights page.

## 📌 Key Business Insights

Some major highlights from the report:
- West region is the **highest contributor** in sales
- Technology category dominates overall sales
- Central region shows **poor profit margins**
- NYC is the city with the **highest order volume**
- Sales have grown significantly from **2015 to 2017**

> For the full list of insights, visit the **Insights Page** via the 💡 icon.

## 🗂️ How to Use

1. Open `Superstore Power BI Report.pbix` in Power BI Desktop
2. Use filters at the top to interact with the data
3. Hover over visuals for tooltips
4. Click the **💡 bulb icon** to view Top 10 Insights

## 📦 Dataset Source
This report uses the sample `Superstore Sales` dataset (public dataset often used in Tableau & Power BI demos).

## 📎 Screenshots

### 🔹 Main Dashboard
![Superstore Main Dashboard](SUPERSTORE%20MAIN.png)

### 🔹 Insights Page
![Superstore Insights Page](SUPERSTORE%20INSIGHTS.png)

## 📥 Optional Enhancements
- Add **filled map** to show geospatial sales distribution
- Introduce **drillthrough pages** for product-level deep dives



