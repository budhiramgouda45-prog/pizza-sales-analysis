#  🍕 Pizza Sales Analysis Dashboard

This project presents an end-to-end **Pizza Sales Analysis** using Power BI** and **SQL**
The objective is to analyze pizza sales data, identify business trends, and build an interactive dashboard that helps understand revenue, orders, and product performance.

## 📌 Project Overview

The **Pizza Sales Analysis** project focuses on transforming raw sales data into meaningful insights using data cleaning, SQL analysis, and visualization techniques.

The dashboard highlights:

- Sales performance across different pizza categories
- Revenue trends over time
- Customer order patterns
- Best and worst performing pizza types

This project demonstrates a real-world data analytics workflow:
**Raw Data → Data Cleaning → SQL Analysis → Visualization**

## ❓ Business Questions Solved

- What is the total revenue generated?
- What is the average order value?
- What is the total pizzas sold?
- What is the total number of orders?
- What is the average pizzas per order?
- Which pizza category contributes the most sales?
- Which pizza size is most popular?
- What are the top 5 and bottom 5 pizzas by revenue, quantity, and total orders?
- What are the peak order days and months?

## 📂 Dataset

The dataset contains pizza order transaction details with columns such as:

- Order_ID  
- Order_Date  
- Pizza_Name  
- Pizza_Category  
- Pizza_Size  
- Quantity  
- Total_Price  

Files included:

- `pizza_sales_data_raw.csv` → Original dataset  
- `pizza_sales_data_clean.csv` → Cleaned dataset used for analysis
- Pizza_Sales_Analysis_Dashboard.pbix → Power BI dashboard file
-  SQL-QUERIES.docx → SQL queries used for analysis

## 🧹 Data Cleaning Process

Data was cleaned using **Power Query** in Power BI:

- Removed null values
- Corrected data types
- Standardized column names
- Removed duplicates
- Created calculated columns


 ## 🔍 SQL Analysis

SQL queries were used to calculate KPIs and trends such as:

- Total Revenue
- Average Order Value
- Sales by Category
- Sales by Pizza Size
- Top & Bottom Performing Pizzas

File location:[https://github.com/budhiramgouda45-prog/pizza-sales-analysis/blob/main/SQL-QUERIS.docx](https://github.com/budhiramgouda45-prog/pizza-sales-analysis/blob/main/PIZZA%20SALES%20SQL-QUERIES.docx)

## Key DAX Measures

 Some important DAX calculations used in the dashboard:

 Total Revenue = SUM(pizza_sales_data_clean[Total_Price])
 Total Orders = DISTINCTCOUNT(pizza_sales_data_clean[Order_ID])
 Total Quantity = SUM(pizza_sales_data_clean[Quantity])
 Average Order Value = 
 DIVIDE([Total Revenue], [Total Orders])

## 📈 Power BI Dashboard

The interactive dashboard was built using **Power BI Desktop** and includes:

- KPI Cards
- Bar Charts
- Line Charts
- Category Analysis
- Filters & Slicers

To view the dashboard:
1. Download the `.pbix` file  
2. Open using Power BI Desktop

## 📸 Dashboard Preview

<img width="852" height="482" alt="Dashboard1" src="https://github.com/user-attachments/assets/34cf134c-d1ca-4a49-bc8c-cc487a53a3ae" />

[<img width="850" height="481" alt="Dashboard2" src="https://github.com/user-attachments/assets/fdc90f5f-5789-4a6a-9af0-3dd885c8f7a5" />
](https://github.com/budhiramgouda45-prog/pizza-sales-analysis/blob/main/Dashboard2.png)



## 🛠️ Tools & Technologies Used

| Tool         | Purpose |
|------------- |---------|
| Power BI     | Data Visualization |
| SQL          | Data Analysis |
| Power Query  | Data Cleaning |
| Excel/CSV    | Data Source |
| GitHub       | Project Hosting |


## 👨‍💻 Author

**Budhiram Gouda**

Aspiring Data Analyst skilled in:
- SQL  
- Power BI  
- Excel
- Python
- Data Cleaning & Visualization  

---

## 📄 License

This project is open-source and available for learning purposes.
