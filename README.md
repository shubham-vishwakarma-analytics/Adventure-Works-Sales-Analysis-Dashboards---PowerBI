# 📈 Adventure Works Sales Analysis (Power BI)

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811.svg)](dashboard/Adventure_Works_Sales_Analysis.pbix)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)](dashboard/Adventure_Works_Sales_Analysis.pbix)

## 📌 Project Overview
An interactive Power BI dashboard analyzing Adventure Works sales data across customers, products, categories, and regions — built with dynamic axis selection, bookmarks, and drill-through navigation.

---

## 🗂 Repository Structure
```
├── dashboard/     # The Power BI (.pbix) file
├── datasets/      # Source CSVs used to build the model
├── screenshots/   # Static previews of each dashboard page
├── demo/          # Animated GIF walkthroughs of the dashboard
└── README.md
```

---

## 🎬 Live Demo
![Dashboard Demo](demo/Dashboard_Demo.gif)

---

## 🖥️ Dashboard Pages

### 🏠 Home Page
Navigation hub linking to all report pages.

![Home Page](screenshots/Home-Page.png)

### 👤 Customer Analysis
Revenue by top customer, gender-wise order distribution, and orders by annual income, with slicers for category, year, and gender.

![Customer Analysis](screenshots/Customer-Analysis.png)

### 📦 Product Analysis
Weekly product returns and weekly profit trends, with most profitable product/category and most ordered product called out.

![Product Analysis](screenshots/Product-Analysis.png)

### 🗂 Category Analysis
Return rate, revenue, sold quantity, and bulk orders broken down by category (Accessories, Bikes, Clothing), filterable by day type and year.

![Category Analysis](screenshots/Category-Analysis.png)

### 🌍 Maps
Country-wise order distribution shown geographically.

![Maps](screenshots/Maps.png)

### 📊 Dynamic X-Axis / Y-Axis
Lets users swap the chart's X and Y axis fields on the fly (category, education level, gender, revenue, profit, and more).

![Dynamic X Axis](screenshots/Dynamic-X.png)
![Dynamic Y Axis](screenshots/Dynamic-Y.png)

### 📉 Dynamic Chart
Combined view showing Annual Income, Return Amount, Profit, Revenue, Sold Qty, Total Cost, and Total Orders by Gender and Education Level.

![Dynamic Chart](screenshots/Dynamic-Chart.png)

### 🔖 Bookmarks
Quick-jump buttons (Overall, Accessories, Bike, Clothing) for saved report views.

![Bookmarks](screenshots/Bookmarks.png)

---

## 📊 Dataset
Source data used to build the model, found in [`datasets/`](datasets/):
- `AdventureWorks_Calendar.csv`
- `AdventureWorks_Customers.csv`
- `AdventureWorks_Products.csv`
- `AdventureWorks_Product_Categories.csv`
- `AdventureWorks_Product_Subcategories.csv`
- `AdventureWorks_Returns.csv`
- `AdventureWorks_Sales_2015.csv`
- `AdventureWorks_Sales_2016.csv`
- `AdventureWorks_Sales_2017.csv`
- `AdventureWorks_Territories.csv`

---

## 🛠️ Tools Used
- Power BI Desktop
- DAX (dynamic measures for axis switching)
- Power Query (data cleaning & modeling)

---

## 👤 Author
**Shubham Vishwakarma**
Aspiring Data Analyst | Power BI Enthusiast
