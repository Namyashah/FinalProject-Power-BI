## 📸 Dashboard Preview

![Dashboard Screenshot](images/Screenshot%202025-06-19%20235519.png)

# 📊 FinalProject - Power BI Dashboard

Welcome to the **FinalProject Power BI Dashboard**! This project is a deep dive into business insights using sales and returns data. It visualizes key performance metrics, customer trends, product performance, and much more — all built with Power BI! 🚀

---

## 🧠 Objective

This dashboard aims to:

- Analyze **Sales Performance** 📈
- Track **Returns Trends** 🔁
- Understand **Customer Behavior** 🧍‍♂️🧍‍♀️
- Compare regional performance 🌍
- Utilize Time Intelligence for **YOY**, **YTD**, and **MTD** tracking 🕒

---

## 📁 Project Structure

Here's an overview of the folder and file organization:

```
FinalProject/
│
├── FinalProject.pbix                       # The Power BI dashboard file
├── README.md                               # 📄 You are here!
├── /Dataset
│   ├── FinalProject_Dataset - Customer_Dim.csv
│   ├── FinalProject_Dataset - Date_Dim.csv
│   ├── FinalProject_Dataset - Product_Dim.csv
│   ├── FinalProject_Dataset - Region_Dim.csv
│   ├── FinalProject_Dataset - Sales_Fact.csv
│   └── FinalProject_Dataset - Returns_Fact.csv
└── /Assets
    └── screenshot.png                      # Dashboard snapshot
```

---

## 🧱 Data Model Overview

Your project follows a **star schema** structure with the following tables:

### 🧩 Dimension Tables

| Table Name         | Description                              |
|--------------------|------------------------------------------|
| `Customer_Dim`     | Contains customer information like ID, name, and segments |
| `Date_Dim`         | Calendar-based fields for time intelligence |
| `Product_Dim`      | Product category, subcategory, and details |
| `Region_Dim`       | Regional breakdowns for sales and returns |

### 📦 Fact Tables

| Table Name         | Description                              |
|--------------------|------------------------------------------|
| `Sales_Fact`       | Core table tracking sales transactions 💰 |
| `Returns_Fact`     | Records of returned products 🚚🔁 |

---

## 🧠 Key Features & Insights

✅ **Sales Analysis**  
- Total Sales, Profit, Quantity Sold  
- Top-performing products and customers  
- Sales by Category, Subcategory  

✅ **Returns Tracking**  
- Return rate by product and region  
- Monthly return trend  

✅ **Customer Insights**  
- Segmentation-based filtering  
- Lifetime value analysis  

✅ **Time Intelligence**  
- YOY (Year Over Year) Growth  
- YTD (Year to Date) Metrics  
- MTD (Month to Date) Comparisons  
- Seasonal Trends  

✅ **Interactive Filters**  
- Slicers by Region, Product Category, Date  
- Drill-through pages for deep insights  

---

## ⚙️ Tools & Technologies Used

- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query for ETL**  
- **CSV Files as Data Source**

---

## 📌 Notes

- Ensure all `.csv` files are placed correctly when refreshing data.
- The relationships between tables are defined via Power BI Model View.
- This dashboard is dynamic and supports drill-down for detailed insights.

---

## 🙌 Thank You

Thanks for exploring my Power BI project!  
If you liked it, feel free to connect or share feedback. 😄
