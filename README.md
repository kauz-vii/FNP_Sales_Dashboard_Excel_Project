# 🌸 FNP Sales Dashboard (Excel Project)

<p align="center">
  <img src="https://raw.githubusercontent.com/kauz-vii/FNP_Sales_Dashboard_Excel_Project/main/fnp-logo.jpg" width="150"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Excel-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Level-Beginner--Intermediate-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Data%20Analytics-orange?style=for-the-badge"/>
</p>

## 📌 Project Overview

This project analyzes sales data from **Ferns N Petals (FNP)**—an online gifting platform—using **Microsoft Excel**.

It demonstrates a complete **end-to-end data analytics workflow**, including:

- 🔹 Data Extraction (Power Query)  
- 🔹 Data Cleaning & Transformation (ETL)  
- 🔹 Data Modeling (Power Pivot)  
- 🔹 Data Analysis (Pivot Tables)  
- 🔹 Dashboard Creation (Charts & Slicers)  

📊 The final output is an **interactive Excel dashboard** that provides actionable business insights.

<p align="center">
  <a href="https://github.com/kauz-vii/FNP_Sales_Dashboard_Excel_Project/blob/main/Insights.md">
    <img src="https://img.shields.io/badge/For%20Key%20Insights%20with%20Business%20Impact%20%7C%20Click%20Here-blue?style=for-the-badge" />
  </a>
</p>

## 🎯 Objectives

- Design a structured data model using multiple datasets  
- Clean and transform raw data into usable format  
- Analyze sales trends and customer behavior  
- Build an interactive dashboard for decision-making  
- Extract meaningful business insights  

---

## 🗂️ Dataset

The project uses **3 datasets**:

| Dataset     | Description |
|------------|------------|
| Customers  | Customer details (Name, City, Gender, Contact) |
| Orders     | Order info (Date, Time, Quantity, Occasion) |
| Products   | Product details (Category, Price, Occasion) |

---

## ⚙️ Workflow

### 🔹 1. Data Extraction
- Imported multiple CSV files using **Power Query (From Folder)**
- Enabled dynamic updates for new data

### 🔹 2. Data Cleaning
- Removed unnecessary columns  
- Handled inconsistencies and data types  
- Checked duplicates & null values  

### 🔹 3. Data Transformation
- Created new features:
  - Month of Order  
  - Hour of Order  
  - Delivery Time (Days)  
- Merged datasets to bring **price into Orders**
- Created:

Revenue = Price × Quantity

### 🔹 4. Data Modeling
- Built **Star Schema** using Power Pivot:

        Customers
            |
            |
        Products —— Orders (Fact Table)

### 🔹 5. Data Analysis
Performed analysis using Pivot Tables:

- Total Revenue  
- Monthly Sales Trends  
- Top Products  
- Customer Spending  
- Delivery Time Analysis  
- City-wise Orders  
- Occasion-based Sales  

---

## 📊 Dashboard Features

- 📈 Revenue Trends (Monthly Line Chart)  
- 🛍️ Top Products Analysis  
- 🎉 Occasion-based Sales  
- 🏙️ Top Cities by Orders  
- ⏱️ Delivery Time Insights  
- 🎯 KPI Cards:
  - Total Revenue  
  - Total Orders  
  - Avg Delivery Time  
  - Avg Customer Spending  

- 🔍 Interactive Filters:
  - Slicer (Occasion)  
  - Timeline (Date filter)  

---

## 📸 Dashboard Preview


![](https://github.com/kauz-vii/FNP_Sales_Dashboard_Excel_Project/blob/main/Dashboard-screenshot.jpg)

---

## 📌 Key Insights

- 📅 Sales peak during festive occasions (Diwali, Valentine’s Day, Raksha Bandhan)  
- 💰 Few products generate majority of revenue  
- 🧍 Average customer spending ≈ ₹3500  
- 🚚 Average delivery time ≈ 5–6 days  
- 🌍 Certain cities contribute most orders  
- 📊 Weak correlation between quantity & delivery time  

---

## 🛠️ Tools & Technologies

- Microsoft Excel  
- Power Query (ETL)  
- Power Pivot (Data Modeling)  
- Pivot Tables  
- Basic DAX  

---

## 🚀 How to Use

1. Download the dataset  
2. Open Excel → Data → Get Data → From Folder  
3. Perform cleaning & transformations in Power Query  
4. Load data into Data Model  
5. Create relationships using Power Pivot  
6. Build Pivot Tables  
7. Design dashboard with charts & slicers  

---

## 👨‍💻 Author

Kaushik Bhadra

- Aspiring Data Analyst  
- Interested in Data Analytics, SQL & Dashboarding  

---

## ⭐ Project Value

This project demonstrates:

- Real-world data analysis workflow  
- Strong Excel & dashboarding skills  
- Business insight generation  
- Data modeling using Star Schema  

---

## 📢 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/kaushikbhadra07" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Kaushik%20Bhadra-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>

