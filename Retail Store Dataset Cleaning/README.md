# Retail Store Dataset Cleaning & Analysis

This project involves data cleaning, exploratory data analysis, and preparation of the Online Retail dataset using Python and Pandas in Jupyter Notebook.

## Project Overview
The goal of this project is to clean raw transactional retail data to ensure accuracy, consistency, and readiness for business analysis and visualization.

## Dataset Information
* **File Name:** `Online Retail.xlsx`
* **Columns:**
  * `InvoiceNo`: Invoice number (a 6-digit integral number uniquely assigned to each transaction; cancellations start with 'C').
  * `StockCode`: Product code (a 5-digit integral number uniquely assigned to each distinct product).
  * `Description`: Product (item) name.
  * `Quantity`: The quantities of each product per transaction.
  * `InvoiceDate`: Invoice date and time.
  * `UnitPrice`: Product price per unit.
  * `CustomerID`: Customer number (a 5-digit integral number uniquely assigned to each customer).
  * `Country`: Country name where each customer resides.

## Steps Performed
1. **Data Loading:** Loaded the dataset using `pandas.read_excel()`.
2. **Data Inspection:** Explored the dataset shape, data types, head, and tail to understand the structure.
3. **Handling Missing Values:** Checked for null values across all columns and filled missing fields where appropriate.
4. **Removing Duplicates:** Identified and removed duplicate rows to maintain data integrity.
5. **Data Type Formatting:** Converted columns like `InvoiceDate` to the correct datetime format.

## Technologies Used
* Python
* Pandas
* NumPy
* Jupyter Notebook
