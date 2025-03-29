# BlinkIT-Grocery-Dashboard
This dashboard created using the BlinkIt data helps to visualize the data easily to understand the sales, customer preferences, performance of the different tyre stores, total revenue, etc.
## 📊 Project Overview

This Power BI dashboard analyzes sales performance across different product types, outlet categories, and location types for one of the biggest online grocery retailer and delivery platform, **BlinkIT**.  
The dashboard is connected to a local **SQL Server 2022** database and demonstrates SQL integration with Power BI for real-time data modeling and visualization.

---

## 🛠️ Tools & Technologies Used

- Microsoft Power BI
- SQL Server 2022 (Developer Edition)
- SQL Server Management Studio (SSMS)
- Excel (initial data source)

---

## 🧠 Key Insights

- 🏪 **Tier 3 outlets** show the highest average sales performance.
- 🥤 **Soft drinks** and **packaged foods** dominate in total revenue.
- 🍔 **Regular fat content** products consistently outperform low-fat ones.
- 🗺️ Sales distribution varies significantly by **location type** and **outlet size**.

---

## 🧩 How to Use This Project

### 1. Setup SQL Server & Import Data

- Open **SSMS** and run the provided script:
  - `BlinkIT_Grocery_Data_Insert_FULL.sql`
- This script will:
  - Create the table `BlinkIT_Grocery_Data`
  - Insert all records from the dataset

### 2. Open the Power BI File

- File: `BlinkIT_Grocery_Dashboard_SQL.pbix`
- Power BI will connect to your local SQL Server (make sure SQL Server is running)

### 3. Refresh Data

- Click **Refresh** in Power BI
- Dashboard will populate from the SQL table

---

## 📁 Folder Contents

| File Name                           | Description                                   |
|-------------------------------------|-----------------------------------------------|
| `Blinkit_Visualization.pbix`        | Power BI dashboard connected to SQL Server    |
| `BlinkIT_Grocery_Data_Insert.sql`   | SQL script to create table and insert data    |
| `BlinkIT Grocery Data.xlsx`         | Original dataset file provided for study      |
|                                     | purpose in the Data Tutorials Youtube channel |
| `README.md`                         | This documentation file                       |

---

## 📌 About the Dataset

Originally sourced from an Excel workbook which was given by the Youtube channel "Data Tutorials", the data has been transformed into a relational format for better scalability and integration with SQL-based analytics platforms.
