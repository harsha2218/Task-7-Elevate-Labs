# 🛒 SQL + Python Sales Data Analysis

A mini project demonstrating how to use **SQL inside Python** to analyze sales data and visualize results.

---

## 🎯 Objective
Use SQL queries within Python to calculate:
- Total quantity sold  
- Total revenue per product  

Then display the results using print statements and a simple **Matplotlib bar chart**.

---

## 🧰 Tools Used
- Python  
- SQLite (built-in)  
- Pandas  
- Matplotlib  

---

## 🗂️ Dataset
A small SQLite database file **`sales_data.db`** containing one table:

| Column   | Type  | Description          |
|-----------|--------|----------------------|
| product   | TEXT   | Product name         |
| quantity  | INT    | Units sold           |
| price     | REAL   | Price per unit (USD) |

---

## ⚙️ Steps Performed
1. Connected to SQLite database using `sqlite3`  
2. Created a simple `sales` table  
3. Inserted sample sales records  
4. Executed SQL query to calculate `total_qty` and `revenue`  
5. Loaded results into a Pandas DataFrame  
6. Displayed the summary in console  
7. Plotted a **bar chart** showing revenue by product  

---


## 📁 Deliverables
- Python Script / Notebook
- SQLite Database (sales_data.db)
- Bar Chart (sales_chart.png)

---
