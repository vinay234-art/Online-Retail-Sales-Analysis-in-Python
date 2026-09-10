# 🛍️ Online Retail Sales Analysis

## 📌 Project Overview

This project focuses on analyzing online retail sales data using Python. The objective is to clean, explore, analyze, and visualize retail transaction data to identify important sales patterns, customer behavior, product performance, and country-wise sales trends.

The analysis was performed using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.

## 📊 Dataset

The dataset contains online retail transaction records with the following columns:

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country

The original dataset contains **541,909 records and 8 columns**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔄 Data Cleaning & Preparation

The following data preparation steps were performed:

* Loaded the retail sales dataset using Pandas.
* Checked the shape and structure of the dataset.
* Examined data types and statistical summaries.
* Converted `InvoiceDate` into datetime format.
* Removed duplicate records.
* Checked missing values.
* Identified negative values in `Quantity` and `UnitPrice`.
* Replaced negative values with 0.
* Created `Month` and `Day` columns from `InvoiceDate`.
* Created a `TotalAmount` column using:

`TotalAmount = Quantity × UnitPrice`

The cleaned dataset was then saved for further analysis.

## 🔎 Exploratory Data Analysis

The project includes analysis of:

* Total quantity sold
* Average unit price
* Maximum quantity purchased in a transaction
* Minimum and maximum unit price
* Top 10 products based on quantity sold
* Top 5 countries based on transactions
* Customer with the highest purchased quantity
* Most frequently purchased product
* Total sales/revenue
* Average order-related quantity
* Country-wise total sales
* Month-wise total sales

For example, the analysis identified **PAPER CRAFT, LITTLE BIRDIE** as the product with the highest total quantity in the analyzed data, with 80,995 units.

The analysis also shows that **United Kingdom** generated the highest total sales among the countries in the dataset.

## 📈 Sales Analysis

A `TotalAmount` column was created by multiplying `Quantity` and `UnitPrice`.

The calculated total sales in the notebook are approximately **10.64 million**.

Monthly sales analysis was also performed. The highest monthly sales in the notebook occur in **November**, followed by December.

## 📊 Data Visualization

The project uses Matplotlib and Seaborn for visual analysis.

Visualizations include:

* Box Plot of Quantity
* Box Plot of UnitPrice
* Product-based analysis charts
* Country-wise sales visualization
* Monthly sales visualization

The notebook also uses customized chart titles and axis labels for better readability.

## 💡 Key Insights

Based on the analysis:

* The dataset contains more than **500K retail transaction records**.
* Duplicate records were removed during data cleaning.
* Negative Quantity and UnitPrice values were identified and handled.
* The dataset covers multiple countries.
* United Kingdom contributes the largest share of total sales.
* Product quantity varies significantly across transactions.
* PAPER CRAFT, LITTLE BIRDIE has the highest quantity sold in the analysis.
* November records the highest monthly sales.
* Customer-level analysis was performed to identify high-volume customers.

## 🎯 Project Objectives

The main objectives of this project are:

1. Understand the structure of online retail transaction data.
2. Clean and prepare the dataset for analysis.
3. Analyze product and customer purchasing behavior.
4. Identify high-performing products.
5. Analyze country-wise sales performance.
6. Analyze monthly sales trends.
7. Create meaningful visualizations from the data.
8. Generate business-oriented insights from retail transactions.

## 📁 Project Files

```text
Online-Retail-Sales-Analysis/
│
├── Online Retail Sales Analysis.ipynb
├── Cleaned_Sales_data.csv
└── README.md
```

## 🚀 Conclusion

This project demonstrates the use of Python for **data cleaning, exploratory data analysis, business analysis, and data visualization**. The analysis provides useful insights into product performance, customer purchasing behavior, geographical sales distribution, and monthly sales trends.

This project was created as part of my **Data Analytics learning journey** and demonstrates practical experience with Python, Pandas, NumPy, Matplotlib, and Seaborn.
