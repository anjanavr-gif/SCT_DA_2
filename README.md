#  Data Cleaning and Preparation using Python (Pandas)

## Task 02 – SkillCraft Data Analytics Internship

##  Project Overview
This project focuses on cleaning and preparing raw data using **Python (Pandas)** in Google Colab. The dataset used is the **Global Superstore dataset**.

The objective is to improve data quality and transform raw data into a clean and structured format suitable for analysis.

---

##  Tools & Technologies
- Python  
- Pandas  
- Google Colab  

---

##  Data Cleaning Process

### 1. Data Loading
- Loaded dataset into Pandas DataFrame  

### 2. Data Exploration
- Viewed dataset using `.head()`  
- Checked structure using `.info()`  
- Reviewed column names  

### 3. Handling Missing Values
- Identified missing values using `.isnull().sum()`  

### 4. Removing Unnecessary Columns
- Dropped `Postal Code` column  

### 5. Removing Duplicate Records
- Checked duplicate rows using `.duplicated()`  

### 6. Cleaning Column Names
- Converted column names to lowercase  
- Replaced spaces with underscores  
- Removed extra spaces  

### 7. Data Cleaning
- Removed leading and trailing spaces from text columns  

### 8. Data Type Conversion
- Converted `order_date` and `ship_date` to datetime format  

---

## Files in Repository
- `Global Superstore.xls` → Raw dataset  
- `task2.ipynb` → Cleaning process using Pandas  
- `cleaned_superstore(1).csv` → Final cleaned dataset  

---

##  Outcome
- Cleaned and structured dataset  
- Missing values identified  
- Duplicate records checked  
- Standardized column names  
- Correct data types applied  
- Dataset ready for analysis  

---

##  Conclusion
This project demonstrates how **Pandas** can be effectively used to clean and prepare raw data, making it suitable for further analysis and visualization.

---

##  Author
**Anjana V R**
