# Customer Segmentation Analysis Using RFM and K-Means

## Oasis Infobyte Internship — Data Analytics Track

## 📌 Project Overview

This project performs customer segmentation using transactional e-commerce data.

RFM (Recency, Frequency, Monetary) analysis is used to understand customer purchasing behavior, followed by K-Means clustering to divide customers into meaningful behavioral segments.

The objective is to help businesses develop targeted marketing and customer-retention strategies.

## 🎯 Objectives

- Clean and prepare transactional data
- Analyze customer purchasing behavior
- Calculate Recency, Frequency, and Monetary values
- Standardize RFM features
- Determine the optimal number of clusters using the Elbow Method
- Apply K-Means clustering
- Profile customer segments
- Visualize customer clusters
- Develop targeted marketing recommendations

## 🗂️ Dataset

The project uses the **UCI Online Retail Dataset**.

The dataset contains transactional records from an online retailer and includes information such as:

- Invoice number
- Product code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

The dataset is publicly available through the UCI Machine Learning Repository.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## 🔍 Methodology

### 1. Data Cleaning

The dataset was inspected and cleaned by handling:

- Missing customer IDs
- Cancelled transactions
- Invalid quantities
- Invalid prices
- Duplicate records
- Date formatting

### 2. RFM Analysis

Three customer-level behavioral features were calculated:

**Recency:** How recently a customer made a purchase.

**Frequency:** How frequently a customer made purchases.

**Monetary:** How much money a customer spent.

### 3. Feature Scaling

RFM variables were standardized using `StandardScaler` so that variables with different numerical scales would contribute appropriately to clustering.

### 4. K-Means Clustering

The Elbow Method was used to determine a suitable number of customer clusters.

K-Means clustering was then applied to the standardized RFM features.

### 5. Customer Profiling

Each cluster was analyzed based on:

- Average Recency
- Average Frequency
- Average Monetary value
- Customer count

### 6. Business Recommendations

Marketing strategies were developed for each customer segment based on its purchasing behavior.

## 📊 Key Analysis

The project includes:

- Customer purchasing statistics
- RFM distributions
- Elbow Method visualization
- Customer cluster sizes
- RFM cluster profiles
- Recency vs Frequency visualization
- Frequency vs Monetary visualization
- Recency vs Monetary visualization
- Customer segment recommendations

## 💡 Business Value

Customer segmentation can help businesses:

- Identify high-value customers
- Improve customer retention
- Develop personalized marketing campaigns
- Identify customers at risk of becoming inactive
- Improve cross-selling and upselling opportunities
- Allocate marketing resources more effectively

## ⚠️ Limitations

- The analysis focuses primarily on purchasing behavior.
- Demographic information is limited.
- K-Means requires selecting an appropriate number of clusters.
- Customer behavior can change over time.
- Clustering results depend on preprocessing and feature selection.

## 👨‍💻 Author

**Adithya Vardhan**

B.Tech — Artificial Intelligence & Data Science

## 📌 Internship

This project was completed as part of the:

**Oasis Infobyte — Data Analytics Internship Program**
