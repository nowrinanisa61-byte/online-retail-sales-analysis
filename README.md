# 📊 Online Retail Sales Analysis

## 📌 Project Overview

This project analyzes online retail transaction data using Python to understand sales performance, product performance, customer purchasing behavior, and geographical sales distribution.

The goal is to transform raw transactional data into meaningful business insights that can support data-driven decision-making.

## 🎯 Project Objectives

* Clean and prepare raw retail transaction data
* Analyze overall sales performance
* Identify top-performing products
* Analyze monthly sales trends
* Identify top-performing countries
* Analyze customer purchasing behavior
* Measure repeat customer rate
* Generate actionable business insights

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* **Google Colab**
* **GitHub**

## 🧹 Data Cleaning

The dataset was cleaned before performing the analysis.

Key cleaning steps included:

* Checked for missing values
* Removed cancelled transactions
* Removed transactions with invalid quantities
* Removed transactions with invalid unit prices
* Handled missing Customer IDs for customer-level analysis
* Removed duplicate records
* Created a new **Sales** column using Quantity × UnitPrice
* Converted the InvoiceDate column for time-based analysis

## 📊 Analysis Performed

### 1. Overall Sales Analysis

Calculated the total sales generated from the dataset.

**Total Sales:** £10.64M

### 2. Product Analysis

Identified the products generating the highest revenue.

**Top Product:** REGENCY CAKESTAND 3 TIER

**Top Product Revenue:** £174,156.54

### 3. Monthly Sales Analysis

Analyzed monthly sales trends to understand how sales changed over time.

### 4. Country Analysis

Analyzed sales performance across different countries.

**Top Country:** United Kingdom

**UK Sales:** £9.00M

### 5. Customer Analysis

Analyzed customer purchasing behavior using Customer ID and Invoice Number.

**Unique Customers:** 4,338

**Repeat Customers:** 2,845

**Repeat Customer Rate:** 65.58%

### 6. Average Order Value

Calculated the average revenue generated per invoice.

**Average Order Value:** £533.17

### 7. Customer Segmentation

Customers were segmented into two groups based on purchase frequency:

* **One-time Customer:** Customer with one purchase
* **Repeat Customer:** Customer with more than one purchase

## 💡 Key Business Insights

* The business generated approximately **£10.64 million** in total sales.
* The average order value was approximately **£533.17**.
* The dataset contained **4,338 unique customers**.
* **65.58% of customers were repeat customers**, indicating strong repeat purchasing behavior.
* **REGENCY CAKESTAND 3 TIER** was the highest-revenue product.
* The **United Kingdom** was the dominant sales market, generating approximately **£9.00 million**.
* Approximately **84.6% of total sales came from the United Kingdom**, indicating a high concentration of revenue in the UK market.
* Expanding into other markets could provide opportunities for future growth.

## 📈 Visualizations

The project includes visualizations for:

* Top 10 Products by Revenue
* Monthly Sales Trend
* Top 10 Countries by Revenue
* Top 10 Customers by Revenue
* Customer Segmentation

## 🔍 Conclusion

This project demonstrates how Python and Pandas can be used to clean, analyze, and visualize real-world retail transaction data.

The analysis provides insights into sales performance, product revenue, customer behavior, and geographical market concentration. These findings can help businesses identify high-performing products, understand customer retention, and explore opportunities for market expansion.

## 👩‍💻 Author

**Anisa Nowrin**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
