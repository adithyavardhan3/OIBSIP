# 🧹 Data Cleaning and Preprocessing — Titanic Dataset

## Oasis Infobyte Internship — Data Analytics Track

## 📌 Project Overview

This project demonstrates a systematic data cleaning and preprocessing workflow using the Titanic dataset.

The objective is to identify data-quality issues, handle missing values, remove duplicate records where applicable, standardize data, correct data types, detect outliers, and produce a clean, analysis-ready dataset.

---

## 🎯 Objectives

The main objectives of this project are:

- Perform an initial data-quality assessment
- Identify missing values
- Handle missing data using appropriate strategies
- Detect and handle duplicate records
- Standardize inconsistent values
- Correct inappropriate data types
- Detect numerical outliers using the IQR method
- Document data-cleaning decisions
- Compare the dataset before and after cleaning
- Export the cleaned dataset as a new CSV file

---

## 🗂️ Dataset

The project uses the Titanic dataset.

The dataset contains passenger information including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Cabin
- Embarkation port

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🔍 Data Cleaning Process

### 1. Initial Data Quality Assessment

The original dataset was inspected for:

- Number of rows and columns
- Missing values
- Duplicate rows
- Data types
- Unique values
- Numerical value ranges

### 2. Missing Value Handling

Missing values were analyzed column by column.

An appropriate strategy was selected based on the characteristics of each variable rather than applying the same method to every column.

### 3. Duplicate Removal

Duplicate records were identified and removed only where appropriate.

The number of records before and after duplicate removal was documented.

### 4. Data Standardization

Categorical and text fields were inspected for:

- Extra whitespace
- Inconsistent capitalization
- Unexpected categorical values
- Formatting inconsistencies

### 5. Data Type Correction

Columns were reviewed and converted to appropriate data types where necessary.

### 6. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in numerical variables.

Potential outliers were investigated before deciding whether to retain, cap, or remove them.

### 7. Before vs After Comparison

A data-quality comparison was created to evaluate:

- Row count
- Missing values
- Duplicate records
- Data types
- Invalid values
- Outliers

before and after cleaning.

---

## 📊 Project Outputs

The project produces:

- Initial data-quality report
- Missing-value analysis
- Duplicate analysis
- Data standardization
- Data-type validation
- Outlier analysis
- Before-vs-after comparison
- Cleaned dataset
- Final data-quality validation

---

## 📁 Project Structure

```text
Task3_Data_Cleaning/
│
├── Data_Cleaning.ipynb
├── Titanic_Cleaned.csv
└── README.md
