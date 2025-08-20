# Retail-Sales-Analysis-PowerBI-SQL
# 🛍️ Retail Sales Analysis – Power BI + SQL Project

## 📌 Overview
This project analyzes **Retail Sales Data** using **Microsoft SQL Server** for data storage and transformation, and **Power BI** for visualization.  
The aim is to uncover sales trends, customer behaviors, and product performance to support business decision-making.

---

## 📂 Dataset
- **Source:** [Kaggle Retail Sales Dataset]  
- **File:** `retail_sales_dataset.csv`  
- **Key Columns:**  
  - `TransactionID` → Unique transaction ID  
  - `Date` → Transaction date  
  - `CustomerID` → Unique customer
  - `Gender` → Male or Female
  - `ProductCategory` → Product details (Beauty, Clothing or Eloctronics) 
  - `Quantity`, `PricePerUnit` → Transaction values  
  - `TotalAmount` → Total sales amount  

---

## ⚙️ Tools & Technologies
- **SQL Server** → Data import, cleaning, querying  
- **Power BI** → Data visualization & dashboards  
- **GitHub** → Project hosting and sharing  

---

## 🛠️ Project Workflow
### 1. Data Preparation (SQL Server)
- Imported CSV → `RetailSales` table
- Checked data types & cleaned missing values
- Wrote queries to aggregate sales, customer, and product data

### 2. Data Modeling (Power BI)
- Verified data types (Date, Decimal, Text)
- Created relationships (Customers ↔ Sales)
- Built measures in DAX:
  - `Total Sales = SUM(RetailSales[TotalAmount])`
  - `Total Quantity = SUM(RetailSales[Quantity])`
  - `Average Order Value = DIVIDE([Total Sales], DISTINCTCOUNT(RetailSales[InvoiceID]))`

### 3. Visualization (Power BI)
Built an interactive dashboard with:
- **Line Chart** → Sales trend over time  
- **Bar Chart** → Sales by product category  
- **Pie Chart** → Sales contribution by gender  
- **KPI Cards** → Total Sales, Quantity Sold, Average Order Value  
- **Drill-through Page** → Customer-level insights (CustomerId) 

---

## 📊 Dashboard Insights
✔️ Sales trend analysis by month  
✔️ Best-selling product categories  
✔️ Top customers driving revenue  
✔️ Customer purchase behavior  

---
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1de73269-ccb2-45c6-8248-65cb3fdf926c" />


## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/nisansalasandu/Retail-Sales-Analysis-PowerBI-SQL
.git


