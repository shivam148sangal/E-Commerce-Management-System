# E-commerce Product Management System

A Python-based E-commerce Product Management System with MySQL integration.  
This system **auto-creates** the **database** and **tables**, supports **category, product, customer, and order management**, along with **stock updates, CSV exports, and invoice generation** and provide like **sales analytics, low-stock alerts, top-selling products, customer purchase history, and revenue reports**.  
The system uses a **simple command-line menu** for easy inventory and order handling.

---

## 🚀 Features
- **Category Management** – Add and list product categories.
- **Product Management** – Add, list, search, and update stock.
- **Customer Management** – Add and list customers.
- **Order Management** – Create orders, view details, update status.
- **Sales Analytics** - View revenue, average order value, median, max/min sale, standard deviation, and percentiles.
- **Low-Stock Alerts** - Identify products running low on inventory.
- **Top-Selling Products** - Display top 5 best-selling products.
- **Customer Purchase History** - View detailed orders for each customer.
- **Category Revenue Report** - Generate revenue by category, exportable to Excel.
- **Monthly Sales** - Track monthly revenue, exportable to Excel.
- **Data Export** – Export products and orders to CSV.
- **Invoice Generation** – Generate text invoices for orders.
- **MySQL Integration** – All data stored in MySQL database.

---

## 📦 Requirements
- Python 
- MySQL server
- Python libraries : `mysql-connector-python`, `pandas`, `numpy` 

Install the required library:

     pip install mysql-connector-python
     pip install numpy 
     pip install pandas

---

## ⚙️ Setup

1. Make sure MySQL server is running.
2. Update your MySQL credentials in the script (`DB_USER` and `DB_PASS`):

   ```python
   DB_HOST = "localhost"
   DB_USER = "your_user"
   DB_PASS = "your_password"
   DB_NAME = "ecommerce_db"
   ```
3. Run the program:
   ```bash
   python E-commerce.py
   ```
The program will automatically create the database and tables if they do not exist, and seed sample categories and products.

--- 

## 📋 Menu Options

The main menu includes:

1. List Categories
2. Add Category
3. List Products
4. Add Product
5. Update Product Stock
6. Search Products
7. List Customers
8. Add Customer
9. Create Order
10. List Orders
11. View Order Details
12. Update Order Status
13. Export Products CSV
14. Export Orders CSV
15. Sales Analytics
16. Low Stock Alerts
17. Top 5 Best-Selling Products
18. Customer Purchase History
19. Category-wise Revenue Report
20. Monthly Sales 
21. Exit

---

## 📂 Outputs

* **CSV files** – Products and orders can be exported as `.csv` files.
* **Invoices** – Each orders generate `.txt.` invoices in the current directory.4
* **Excel Reports** - Category revenue and monthly sales trends are exported to Excel (`category_revenue.xlsx`, `monthly_sales.xlsx`).

---
