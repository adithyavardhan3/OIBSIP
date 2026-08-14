# 📊 Superstore Sales — Exploratory Data Analysis

## Oasis Infobyte Internship — Data Analytics Track

## 📌 Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the Superstore sales dataset as part of the Oasis Infobyte Data Analytics Internship.

The objective is to analyze sales performance, customer behavior, product performance, regional trends, and profitability to identify meaningful business insights and provide actionable recommendations.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and quality of the dataset
- Perform data cleaning and validation
- Calculate descriptive statistics
- Analyze monthly and quarterly sales trends
- Analyze customer segments and purchasing behavior
- Identify top-performing products
- Analyze sales by product category and sub-category
- Compare regional sales and profitability
- Study relationships between numerical variables
- Analyze the relationship between discounts and profit
- Generate actionable business recommendations

---

## 🗂️ Dataset

The Superstore dataset contains **9,994 records and 21 columns** covering order, customer, product, sales, discount, and profit information.

### Important Features

| Column | Description |
|---|---|
| Row ID | Unique row identifier |
| Order ID | Unique order identifier |
| Order Date | Date when the order was placed |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| Country | Country |
| City | Customer city |
| State | Customer state |
| Postal Code | Postal code |
| Region | Geographic region |
| Product ID | Product identifier |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Product name |
| Sales | Sales revenue |
| Quantity | Number of units purchased |
| Discount | Discount applied |
| Profit | Profit generated |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

## 🔍 Data Cleaning

The following data-quality checks were performed:

- Checked dataset dimensions
- Checked data types
- Checked missing values
- Checked duplicate rows
- Converted date columns to datetime format
- Validated numerical variables
- Checked sales, quantity, discount, and profit fields

The dataset contained:

- **9,994 rows**
- **21 columns**
- **0 missing values**
- **0 duplicate rows**

---

## 📈 Analysis Performed

### 1. Descriptive Statistics

Calculated:

- Mean
- Median
- Mode
- Standard deviation
- Minimum
- Maximum

for appropriate numerical variables.

### 2. Time-Series Analysis

Analyzed:

- Monthly sales trends
- Quarterly sales trends
- Highest and lowest sales periods

### 3. Customer Analysis

Analyzed:

- Customer segments
- Sales by customer segment
- Average order value by segment
- Number of unique customers
- Top 10 customers by sales
- Customer purchase frequency

### 4. Product Analysis

Analyzed:

- Top 10 products by sales
- Sales by category
- Sales by sub-category
- Quantity sold by category
- Profit by category
- Profit margin by category

### 5. Regional Analysis

Analyzed:

- Sales by region
- Profit by region
- Quantity by region
- Number of orders by region
- Regional profit margin
- Top 10 states by sales

### 6. Correlation Analysis

A correlation heatmap was created to analyze relationships between:

- Sales
- Quantity
- Discount
- Profit

### 7. Additional Business Insight

The relationship between **Discount and Profit** was analyzed to understand the potential impact of discount levels on profitability.

---

## 📊 Key Findings

The analysis produced the following key results:

| Metric | Finding |
|---|---:|
| Total Sales | **$2,297,200.86** |
| Total Profit | **$286,397.02** |
| Best Category | **Technology** |
| Best Customer Segment | **Consumer** |
| Best Region | **West** |
| Top Product | **Canon imageCLASS 2200 Advanced Copier** |
| Highest Sales Month | **November 2017** |

---

## 💡 Business Recommendations

### 1. Prioritize Technology Products

Technology generated the highest sales among the product categories. The company should maintain adequate inventory for high-performing technology products and use targeted promotional strategies.

### 2. Strengthen Consumer Customer Retention

The Consumer segment generated the highest sales. Loyalty programs, personalized offers, and targeted marketing campaigns could help increase customer retention and repeat purchases.

### 3. Focus on the Western Region

The West region recorded the highest sales. The company should maintain strong customer engagement in this region while identifying strategies to improve performance in lower-performing regions.

### 4. Promote High-Performing Products

The Canon imageCLASS 2200 Advanced Copier was the top-selling product by total sales. Maintaining availability and promoting complementary products could help increase revenue.

### 5. Prepare for Peak Sales Periods

November 2017 recorded the highest monthly sales. Historical peak periods should be considered when planning inventory, promotions, staffing, and marketing campaigns.

### 6. Optimize Discount Strategies

Discounts should be evaluated alongside profitability rather than sales alone. Excessive discounts may increase sales volume while reducing profit margins.

---

## ⚠️ Dataset Limitation

The dataset does not contain customer age or gender information.

Therefore, age-group and gender-based analysis could not be performed directly. Instead, customer segmentation, regional analysis, and purchasing behavior were used to understand customer patterns.

---

## 📁 Project Structure

```text
Task1_Retail_Sales_EDA/
│
├── Retail_Sales_EDA.ipynb
└── README.md
