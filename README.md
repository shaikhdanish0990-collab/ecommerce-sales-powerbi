# 🛒 E-Commerce Sales Dashboard | Power BI

An interactive **E-Commerce Sales Dashboard built with Microsoft Power BI** to analyze sales, profitability, orders, products, categories, countries, and platform performance.
-------
## 🎯 Project Overview

The objective of this project is to transform e-commerce transaction data into an interactive Business Intelligence dashboard.

The dashboard helps answer:
- What are total sales, gross profit, profit margin, units sold, and orders?
- Which countries generate the highest revenue and profit?
- Which product categories contribute the most sales?
- Which platforms perform best?
- Which products are the top revenue generators?
- How do sales and profit change month by month?
----------
## 🏢 Business Problem

E-commerce businesses generate large volumes of data across countries, platforms, categories, and products. Raw transaction data makes it difficult to quickly identify trends and performance gaps.

This dashboard provides a visual solution to:
- Monitor sales and profitability KPIs
- Analyze global sales distribution
- Compare platform performance
- Identify top-performing products
- Evaluate category performance
- Compare country-level performance
- Track monthly sales and profit trends
- Support data-driven decisions
-------
## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and KPI calculations
- **Data Modeling** – Analytical data structure
- **Microsoft Excel** – Source data
- **Power BI Visualizations** – KPI Cards, Map, Donut, Column, Line, Bar and Table visuals
-----------
## 📂 Dataset

The dataset contains transaction-level e-commerce information.

Key fields include:
- Date / Year Month
- Country
- Platform
- Product
- Product Category
- Order ID
- Units Sold
- Total Revenue
- Gross Profit

## 🧹 Data Preparation

Power Query was used for data type validation, cleaning, transformation, date preparation, and structuring the data for reporting.
-----------
## 🧮 Key DAX Measures

```DAX
Total Sales =
SUM('Ecommerce Data'[Total Revenue])

Gross Profit =
SUM('Ecommerce Data'[Gross Profit])

Profit Margin % =
DIVIDE([Gross Profit], [Total Sales], 0)

Units Sold =
SUM('Ecommerce Data'[Units Sold])

Total Order =
DISTINCTCOUNT('Ecommerce Data'[Order ID])
```

> Replace table/column names with the exact names in your Power BI model.
-----------
## 📊 Dashboard Features

### 💰 KPI Cards
The dashboard displays:
- **Total Sales:** 1.79M
- **Gross Profit:** 588.35K
- **Profit Margin:** 32.84%
- **Units Sold:** 6,490
- **Total Orders:** 1,000
-----------
### 🌎 Global Sales Distribution
A map visual shows the geographical distribution of sales and helps identify important markets.

### 🏷️ Sales by Category
A donut chart compares sales across Electronics, Home & Kitchen, Sports, Fashion, Beauty, and Books.

### 🛍️ Sales & Profit by Platform
A column chart compares revenue and gross profit across Shopify, eBay, and Amazon.

### 📈 Monthly Sales & Profit Trend
A combined chart tracks monthly revenue and gross profit to identify high/low periods and profitability trends.

### 🏆 Top 10 Products by Sales
A ranked bar chart highlights leading products such as Headphones, Laptop, Smartphone, Tablet, and Smartwatch.

### 🌍 Country Performance
A table compares countries by Orders, Revenue, and Gross Profit.
------------
## 🎛️ Interactive Filters

The dashboard includes:
- Year Month
- Country
- Platform

These slicers allow users to perform dynamic analysis.
-----------
## 💡 Key Business Insights

Based on the dashboard preview:
- Total sales are approximately **1.79M**.
- Gross profit is approximately **588.35K**.
- Overall profit margin is approximately **32.84%**.
- **6,490 units** were sold across **1,000 orders**.
- Electronics is the largest sales category in the displayed view.
- Revenue and profit can be compared across Shopify, eBay, and Amazon.
- Headphones, Laptop, Smartphone, Tablet, and Smartwatch are among the leading products.
- Country-level analysis highlights differences in orders, revenue, and gross profit.
- Monthly analysis helps identify changes in sales and profitability.

> Insights can change when dashboard filters are applied.

## 📸 Dashboard Preview

![E-Commerce Sales Dashboard](https://github.com/shaikhdanish0990-collab/ecommerce-sales-powerbi/blob/main/E-Commerce%20Sales.PNG)

## 🚀 Skills Demonstrated

**Power BI:** Dashboard Development, KPI Reporting, Interactive Reports, Slicers, Data Visualization, Business Intelligence

**DAX:** Measures, SUM, DIVIDE, DISTINCTCOUNT, Filter Context, KPI Calculations

**Power Query:** Data Cleaning, Transformation, Data Preparation

**Data Analytics:** E-Commerce Analytics, Sales Analysis, Profitability Analysis, Product Analysis, Category Analysis, Country Analysis, Platform Analysis, Trend Analysis
----------
## 🎓 Learning Outcomes

This project strengthened my practical understanding of Power BI dashboard development, e-commerce analytics, DAX, Power Query, data modeling, KPI development, product/category analysis, geographic analysis, and business-focused visualization.

## 👤 About Me

I am building my career in **Data Analytics, Power BI, and Business Intelligence**, with hands-on project experience using **Power BI, SQL, Excel, DAX, Power Query, Data Modeling, and Data Visualization**.

### 🎯 Target Roles
- Data Analyst
- Power BI Developer
- BI Analyst
- Business Intelligence Developer

## 🤝 Let's Connect

📌 **LinkedIn:** [https://www.linkedin.com/in/shaikh-danish-power-bi/]

📧 **Email:** [danishsk0092@gmail.com]

**GitHub:** [https://github.com/shaikhdanish0990-collab/Shaikh-Danish-Power-BI]

---

⭐ If you find this project useful, feel free to **star the repository**!

**Data → Insights → Better Business Decisions 📊**
