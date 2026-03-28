# Customer Data Analysis with BigQuery & Python

## Project Overview
This project focuses on extracting, cleaning, and analyzing customer and shopping data using BigQuery and Python.

The goal was to build a simple data pipeline and prepare clean datasets for further analysis.

---

## Tools & Technologies
- Google BigQuery  
- Python  
- Pandas  
- Google Cloud (Service Account)  

---

## Data Sources
- customers table  
- shopping_data table  

---

## Steps Performed

### 1. BigQuery Setup
- Created service account  
- Configured access roles:
  - BigQuery Data Editor  
  - BigQuery Job User  
  - BigQuery Read Session User  

---

### 2. Data Extraction
- Connected to BigQuery using Python  
- Executed SQL queries to retrieve data  

---

### 3. Data Processing
- Merged datasets (customers + shopping data)  
- Removed duplicates  
- Handled missing values  
- Converted data types (e.g. price → float, date → datetime)  

---

### 4. Data Cleaning
- Standardized category values  
- Replaced missing values with "UNKNOWN"  
- Filtered invalid records  

---

## Key Learnings

- How to connect Python to BigQuery  
- Writing SQL queries for data extraction  
- Data cleaning and preprocessing with Pandas  
- Working with real-world messy data  

---

## Project Structure
