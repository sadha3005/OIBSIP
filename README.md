# Retail Sales EDA

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to identify sales trends, customer segment performance, top-selling products, category-wise revenue, and sales distribution.

The project was completed as part of the **OASIS INFOBYTE Data Analytics Internship – Level 1 Task 1**.

## 🎯 Objectives

* Inspect and understand the retail sales dataset
* Analyze sales trends over time
* Identify the highest-performing customer segments
* Find the top 10 products based on sales
* Analyze revenue by product category
* Study relationships between numerical variables
* Understand the distribution of sales
* Provide actionable business recommendations

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Dataset

The dataset contains **9,800 retail sales records** and **18 columns**.

Important columns include:

* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Region
* Product ID
* Category
* Sub-Category
* Product Name
* Sales

## 🔍 Analysis Performed

### 1. Data Inspection

* Dataset shape and structure
* Data types
* Missing-value analysis
* Duplicate-value check
* Descriptive statistics

### 2. Sales Trend Analysis

* Monthly sales trends
* Quarterly sales trends

### 3. Customer Segment Analysis

Sales were analyzed across:

* Consumer
* Corporate
* Home Office

### 4. Top 10 Products

Identified the top 10 products based on total sales.

### 5. Revenue by Category

Compared revenue across:

* Technology
* Furniture
* Office Supplies

### 6. Correlation Analysis

Created a correlation heatmap for numerical variables.

### 7. Sales Distribution

Used a histogram to understand the distribution of sales values.

## 📊 Key Findings

* **Technology** generated the highest total revenue among the three categories.
* The **Consumer** segment contributed the highest sales.
* The **Canon imageCLASS 2200 Advanced Copier** was the highest-selling product by total sales.
* Sales showed fluctuations across months and quarters, with particularly strong performance during 2017 and 2018.
* The sales distribution was right-skewed, indicating that most orders had relatively low sales values while a small number of orders had very high sales values.

## 💡 Business Recommendations

1. **Focus on Technology Products**
   Continue promoting high-performing technology products and consider expanding successful product lines.

2. **Strengthen the Consumer Segment**
   Use targeted offers, loyalty programs, and personalized marketing to increase sales from the Consumer segment.

3. **Promote High-Value Products**
   Use bundles, cross-selling, and targeted promotions to increase the value of high-performing products and transactions.

## ⚠️ Dataset Limitation

The dataset does not contain **Age** or **Gender** columns. Therefore, age-group and gender-based analysis could not be performed. Customer **Segment** was used as an available customer-related attribute instead.

## 📁 Project Files

* `Retail_Sales_EDA.ipynb` – Jupyter Notebook containing the complete analysis
* `retail sales.csv` – Dataset used for the analysis
* `README.md` – Project documentation

## 👩‍💻 Author

**Sadha**
