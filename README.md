# 🛒 Zepto E-commerce Data Analysis Project

## 📌 Project Overview

This project is based on an e-commerce inventory dataset collected from **Zepto**, one of India's quick-commerce platforms. The main goal of this project is to practice SQL by working with a real-world dataset and performing data cleaning, exploration, and business analysis.

Through this project, I learned how data analysts use SQL to understand business data and generate meaningful insights.

---

## 🎯 Objectives

* Create a database and import real-world data
* Explore the dataset using SQL queries
* Clean inconsistent or invalid data
* Analyze product pricing, discounts, inventory, and categories
* Generate business insights using SQL

---

## 📂 Dataset

The dataset was taken from Kaggle and contains information about products available on the Zepto platform.

Each row represents a product with details such as:

* **SKU ID** – Unique product identifier
* **Product Name**
* **Category**
* **MRP**
* **Discount Percentage**
* **Discounted Selling Price**
* **Available Quantity**
* **Weight (grams)**
* **Stock Availability**
* **Package Quantity**

---

## 🛠 Tools Used

* PostgreSQL
* pgAdmin
* SQL
* Kaggle Dataset

---

## 📋 Project Steps

### 1. Database Creation

Created a PostgreSQL database and designed a table with suitable data types to store the inventory data.

### 2. Data Import

Imported the CSV dataset into PostgreSQL using pgAdmin.

### 3. Data Exploration

Performed basic exploration of the dataset by:

* Counting the total number of records
* Viewing sample records
* Finding missing values
* Listing different product categories
* Checking stock availability
* Identifying duplicate product names

### 4. Data Cleaning

Cleaned the dataset by:

* Removing records with invalid prices
* Converting prices from paise to rupees
* Verifying data consistency

### 5. Data Analysis

Used SQL queries to answer business-related questions, such as:

* Top products with the highest discounts
* Products that are out of stock
* Category-wise revenue estimation
* High-priced products with low discounts
* Categories with the highest average discount
* Products offering the best value based on price per gram
* Grouping products by weight
* Total inventory weight for each category

---

## 📊 Skills Demonstrated

* SQL Queries
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Aggregate Functions
* Filtering and Sorting
* GROUP BY and HAVING
* CASE Statements
* Business Insight Generation
* Database Design

---

## 📁 Project Structure

```
Zepto-Data-Analysis/
│
├── zepto_v2.csv
├── zepto_SQL_data_analysis.sql
├── README.md
└── screenshots/
```

---

## 📈 Key Insights

Some insights generated from the analysis include:

* Categories offering the highest discounts
* Products with high MRP but currently out of stock
* Estimated revenue by product category
* Best value-for-money products based on price per gram
* Inventory distribution across different product categories

---

## 📚 What I Learned

This project helped me improve my SQL skills by working with a real-world dataset. I learned how to clean data, write efficient SQL queries, perform exploratory data analysis, and extract business insights that can support decision-making.

---

## 🚀 Future Improvements

* Create interactive Power BI dashboards using the same dataset
* Perform additional analysis using Python (Pandas and Matplotlib)
* Build a complete end-to-end data analytics project by combining SQL, Python, and Power BI

---

## 📌 Conclusion

This project demonstrates my understanding of SQL and data analysis concepts through a real-world e-commerce dataset. It reflects my ability to clean data, analyze business problems, and present meaningful insights, making it a valuable addition to my data analytics portfolio.
