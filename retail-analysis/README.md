# Retail / E-Commerce Sales Data Analysis

## 📌 Project Overview

This project analyzes an online retail sales dataset to uncover business insights such as revenue trends, top-selling products, and customer purchasing patterns.
The analysis is performed using **Python, NumPy, and Pandas**.

The goal of this project is to demonstrate real-world **data cleaning, exploratory data analysis (EDA), and business insight generation** that companies use to make data-driven decisions.

---

## 📊 Dataset

Dataset used: **Online Retail II Dataset**

The dataset contains transaction-level data from an online retail store.

Key columns in the dataset:

* Invoice – Invoice number
* StockCode – Product code
* Description – Product name
* Quantity – Number of items purchased
* InvoiceDate – Transaction date
* Price – Price per item
* Customer ID – Unique customer identifier
* Country – Country of the customer

---

## ⚙️ Tools & Technologies

* Python
* NumPy
* Pandas
* Jupyter Notebook / VS Code

---

## 🧹 Data Cleaning

The following data cleaning steps were performed:

* Removed missing values
* Removed duplicate records
* Filtered out negative quantities (product returns)
* Converted `InvoiceDate` into datetime format
* Created new features: **Year, Month, Revenue**

Revenue was calculated as:

Revenue = Quantity × Price

---

## 📈 Analysis Performed

### 1️⃣ Total Revenue Analysis

Calculated total revenue generated from all transactions.

### 2️⃣ Monthly Sales Trends

Analyzed sales patterns across different months to identify seasonality.

### 3️⃣ Top Selling Products

Identified the products generating the highest revenue.

### 4️⃣ Worst Performing Products

Detected products with the lowest sales performance.

### 5️⃣ Sales by Country

Analyzed which countries contribute the most to revenue.

### 6️⃣ Top Customers

Identified the most valuable customers based on total spending.

### 7️⃣ Average Order Value

Calculated the average revenue per order.

---

## 🧠 Key Business Insights

Some insights discovered from the analysis:

* Certain months generate significantly higher sales due to seasonal demand.
* A small number of products contribute to a large portion of total revenue.
* A few customers generate a high percentage of overall sales.
* The majority of revenue comes from a specific country.

These insights can help companies optimize **inventory, marketing strategies, and customer targeting**.

---

## 📂 Project Structure

retail-analysis
│
├── data
│ └── online_retail_II.xlsx
│
├── notebook
│ └── analysis.ipynb
│
├── README.md

---

## 🚀 Skills Demonstrated

* Data Cleaning with Pandas
* Feature Engineering
* GroupBy Analysis
* Business Data Analysis
* Revenue and Customer Insights

---

## 📌 Future Improvements

* Add visualizations using Matplotlib / Seaborn
* Build an interactive dashboard
* Deploy analysis as a data dashboard

---

## 👨‍💻 Author

Aman Rajbhar
B.Tech Computer Science
Aspiring Data Scientist
