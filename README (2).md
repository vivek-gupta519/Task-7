# Basic Sales Summary with SQLite, Python, and Matplotlib

## 📌 Overview
This project demonstrates how to:
- Create a small SQLite database (`sales_data.db`) with a `sales` table.
- Use SQL inside Python to calculate total quantity sold and total revenue per product.
- Display results in the console and visualize them using a basic bar chart.

---

## 🛠 Tools & Libraries
- **Python 3** (built-in `sqlite3` for database operations)
- **pandas** (for data handling)
- **matplotlib** (for chart plotting)
- **SQLite** (lightweight database engine built into Python)

---

## 📂 Project Files
- **`sales_summary.py`** – Main Python script that:
  1. Creates the SQLite database and inserts sample sales data.
  2. Runs SQL queries to get sales summaries.
  3. Prints results in the console.
  4. Plots and saves a bar chart (`sales_chart.png`).

- **`sales_data.db`** – SQLite database file (created automatically when you run the script).
- **`sales_chart.png`** – Generated bar chart showing revenue by product.

---

## ▶️ How to Run

### 1. Clone or Download
Download this repository or save `sales_summary.py` into your working folder.

### 2. Install Required Libraries
```bash
pip install pandas matplotlib
```

### 3. Run the Script
```bash
python3 sales_summary.py
```

### 4. Output
- **Console Output**: Sales summary table  
- **Chart**: Opens in a window and saves as `sales_chart.png` in the same directory.

Example Console Output:
```
Basic Sales Summary:
   product  total_qty  revenue
0   Apples         15     22.5
1  Bananas         20     16.0
2 Cherries          9     22.5
```

---

## 📊 Chart Example
The generated bar chart shows **Revenue by Product**.

---

## 🎯 Learning Outcomes
By completing this project, you will:
- Understand basic SQL queries inside Python.
- Learn how to import SQL results into pandas DataFrames.
- Perform simple sales data summaries.
- Create and save visualizations with matplotlib.

---
