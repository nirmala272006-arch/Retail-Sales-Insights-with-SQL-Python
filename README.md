# Retail Sales Insights with SQL + Python

**Project Title:** Retail Sales Analysis Project

## 📌 Objective
The purpose of this project is to analyze retail sales data to identify top-selling products, customer behavior, and monthly sales trends.

## 🗄️ Database Schema

**Tables:**

1. **Products**
   - product_id (INTEGER, PRIMARY KEY)
   - name (TEXT)
   - category (TEXT)
   - price (REAL)

2. **Customers**
   - customer_id (INTEGER, PRIMARY KEY)
   - first_name (TEXT)
   - last_name (TEXT)
   - age (INTEGER)
   - city (TEXT)

3. **Sales**
   - sale_id (INTEGER, PRIMARY KEY)
   - sale_date (TEXT)
   - product_id (INTEGER, FK → Products)
   - customer_id (INTEGER, FK → Customers)
   - quantity (INTEGER)
   - total_price (REAL)

## 🔍 SQL Queries and Results
- Best-selling product
- Total sales per category
- Average purchase per customer
- Monthly sales trend

## 📊 Visualizations & Observations

**1. Total Sales by Category**
Electronics and Apparel are the top-selling categories. Accessories have the lowest sales.

**2. Average Purchase per Customer**
Sneha Khan and Asha Patel are the highest spenders. Vikram Singh and Rahul Sharma spend the least.

**3. Monthly Sales Trend**
Sales steadily increased from May to August, with August being the highest month.

## 💡 Business Recommendations
- Focus marketing and stock on top categories (Electronics and Apparel)
- Offer loyalty programs for high-value customers
- Plan promotions during months with lower sales (e.g., June)
- Consider strategies to boost low-selling categories

## 🛠️ Tech Stack
- **SQLite** — database creation and querying
- **Python** — Pandas for data handling
- **Matplotlib** — data visualization

## 📂 File Structure
```
sales_analysis.ipynb   → Notebook with database setup, SQL queries, and visualizations
```

## 🚀 How to Run
1. Open `sales_analysis.ipynb` in Google Colab or Jupyter Notebook
2. Run all cells — the database is created automatically within the notebook (no separate file needed)

## 👤 Author
Nirmala Rathod

**Mentor/Instructor:** Moushreeta
