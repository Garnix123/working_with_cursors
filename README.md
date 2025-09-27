# 📊 Little Lemon Database – Working with Cursors  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)  
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-%23f37626?logo=jupyter)  

---

## 📌 Project Overview  
This project is part of my **Meta Database Engineer Professional Certificate**.  
The focus is on **interacting with a MySQL database (`little_lemon`) from Python** using the `mysql-connector-python` library.  

👉 **Business relevance:**  
- Companies like Little Lemon need reliable access to their databases.  
- Cursor management ensures **efficient queries, proper resource usage, and correct results**.  
- As a Data Analyst / BI professional, understanding this workflow is essential for ETL pipelines, dashboard backends, and scalable data apps.  

---

## 🗂️ Database Context  
- **Database:** `little_lemon`  
- **Example tables used:**  
  - `Bookings`  
  - `Orders`  

The goal is to connect Python to this schema and query existing tables.  

---

## 🛠️ Tech Stack  
- **Python** (Jupyter Notebook)  
- **MySQL Connector/Python** (`mysql.connector`)  
- **MySQL 8.0**  

---

## 📈 Key Learnings
- Unread result found error occurs if results aren’t fetched before running a new query.
- Use buffered=True for convenience in iterative queries.
- Always close cursors to release resources.
- Best practice: pass database="little_lemon" in the connection to avoid USE little_lemon;.

---

## 🎯 Key Insights
- Database connections in Python require careful result handling.
- Buffered cursors are better for iterative development in notebooks.
- These concepts apply directly to real BI workflows (reporting, ETL, dashboard backends).
