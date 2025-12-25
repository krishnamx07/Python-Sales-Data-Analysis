# Python Sales Data Analysis

This project analyzes product sales data using Python.  
The sales data is read from a CSV file, multiple queries are performed using core Python concepts, and finally a new CSV file containing only electronics product data is generated.

---

## Project Objective

- Read sales data from a CSV file
- Perform sales-related queries using Python
- Filter products belonging to the Electronics category
- Generate a new CSV file containing only Electronics sales data

---

## Dataset Used

- **sales_data.csv**  
  Contains product sales details such as:
  - Order date
  - Product name
  - Category
  - Quantity
  - Price
  - Revenue-related values

---

## Technologies Used

- Python
- datetime module
- Jupyter Notebook

> No external libraries are used. All operations are performed using core Python.

---

## Key Operations Performed

- Reading data from a CSV file
- Date-based filtering using the `datetime` module
- Calculating total revenue for a given date range
- Category-based filtering of products
- Writing filtered data to a new CSV file

---

## Output File

- **electronics.csv**  
  This file contains sales data for products belonging only to the Electronics category.

---

## How to Access and Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Python-Sales-Data-Analysis.git
```

### Step 2: Navigate to the Project Directory
```bash
cd Python-Sales-Data-Analysis
```

### Step 3: Open Jupyter Notebook
```bash
jupyter notebook
```

### Step 4: Run the Project
Open and run the following file:
```bash
salesAnalyser.ipynb
```

Navigation Guide

salesAnalyser.ipynb
Main notebook containing all analysis logic and queries

sales_data.csv
Input file containing raw sales data

electronics.csv
Output file generated after filtering Electronics category data

README.md
Project documentation and usage guide

