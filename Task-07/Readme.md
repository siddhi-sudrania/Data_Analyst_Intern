# 🧮 Task 7 – Sales Summary using Python, SQLite, and Pandas

This task demonstrates how to use **Python** with **SQLite** and **Pandas** to generate a basic sales summary and visualize it with **Matplotlib**.

---

## 🔧 Tools & Libraries Used
- Python (3.x) in Jupyter Notebook
- SQLite (sqlite3)
- Pandas
- Matplotlib

---

## 📁 Files Included
- `sales_data.db` – SQLite database created 
- `sales_summary.ipynb` – Python script with SQL queries and visualizations
- `sales_chart.png` – Bar chart showing revenue by product
- `README.md` – You're reading it!

---

## 🧪 What I Did

1. Ran a SQL query to get:
   - Total quantity sold
   - Total revenue per product
2. Ran an additional SQL query to get overall sales totals .
3. Loaded SQL results into Pandas DataFrame.
4. Printed the results to the console.
5. Visualized product-wise revenue using a **bar chart** with Matplotlib.

---

## 📊 Output

```text
📊 Sales Summary by Product:

  product  total_qty  revenue
0   Apple         15      7.5
1  Banana         25      7.5
2  Orange         15      9.0

🧾 Overall Sales Totals:

   grand_total_qty  grand_revenue
0               55           24.0
