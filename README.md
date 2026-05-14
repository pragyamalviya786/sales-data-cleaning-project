# 📊 Sales Data Cleaning Project (Python | Pandas)

## 📌 Project Overview
This project focuses on cleaning and transforming a raw sales dataset using Python and Pandas.  
The objective is to convert messy, inconsistent data into a structured and analysis-ready format for further business insights.

---

## 🧹 Data Cleaning Workflow

### 1. Data Loading & Structure Correction
- Loaded raw dataset (`sales2017_raw.csv`)
- Extracted correct header row from dataset
- Reconstructed dataset structure

### 2. Data Preprocessing
- Removed empty and irrelevant rows
- Handled missing values
- Standardized dataset structure

### 3. Column Standardization
- Converted column names to lowercase
- Removed spaces and special characters
- Renamed inconsistent column names for clarity

### 4. Data Type Conversion
- Converted numeric fields (sales, revenue, stock, price) to proper data types
- Converted order_date column into datetime format

### 5. Data Cleaning Operations
- Cleaned text values in sales column
- Removed duplicate records
- Dropped unnecessary columns

### 6. Data Analysis (Basic)
- Calculated total sales grouped by product_id
- Performed basic dataset inspection using `info()`, `describe()`, and null value analysis

---

## 🛠️ Tools & Technologies Used
- Python  
- Pandas  
- VS Code  

---

## 📁 Output File
- `sales_clean.csv` → Final cleaned and structured dataset

---

## 🎯 Key Outcome
The raw sales dataset has been successfully transformed into a clean, consistent, and analysis-ready format suitable for business reporting and data analysis.

---

## 👩‍💻 Author
Pragya Malviya
