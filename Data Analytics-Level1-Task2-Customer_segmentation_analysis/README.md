
# Customer Segmentation using RFM Analysis and K-Means Clustering

## Project Overview

Customer Segmentation is a data analytics project that groups customers based on their purchasing behaviour.

In this project, **RFM Analysis** and **K-Means Clustering** are used to identify different customer segments based on:

- **Recency** – How recently a customer made a purchase
- **Frequency** – How frequently a customer purchases
- **Monetary** – How much a customer spends

The identified customer groups help businesses understand customer behaviour and develop targeted marketing strategies.

---

## Objective

The main objectives of this project are:

- Analyze customer purchasing behaviour.
- Calculate Recency, Frequency, and Monetary (RFM) values.
- Segment customers using K-Means clustering.
- Identify high-value, loyal, regular, and at-risk customers.
- Provide actionable business recommendations for each segment.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Methodology

### 1. Data Preparation

The customer transaction data was loaded and prepared for analysis.

The data was checked for:

- Missing values
- Duplicate records
- Data types
- Data consistency

### 2. RFM Analysis

RFM analysis was performed using three important customer metrics:

**Recency:** Measures how recently the customer made a purchase.

**Frequency:** Measures how often the customer makes purchases.

**Monetary:** Measures the total amount spent by the customer.

### 3. Customer Segmentation

K-Means clustering was applied to the RFM values to group customers with similar purchasing behaviour.

The resulting clusters were analyzed and assigned meaningful customer segment names.

---

## Customer Segments

### Cluster 0 – Regular / Moderate Customers

This is the **largest customer segment**, with moderate recency, purchase frequency, and spending.

These customers represent a major portion of the customer base and provide an opportunity to increase their purchase frequency and overall spending.

### Cluster 1 – At-Risk / Inactive Customers

These customers have not purchased recently and have relatively low purchase frequency and spending.

They may require targeted re-engagement strategies to encourage them to return.

### Cluster 2 – VIP / High-Value Customers

Although this segment contains only a small number of customers, they have extremely high purchase frequency and monetary value.

These customers are highly valuable to the business and should receive special attention and retention strategies.

### Cluster 3 – Loyal Customers

These customers purchase frequently, have recent transactions, and generate significant revenue.

They represent an important customer group with strong engagement and loyalty.

---

## Actionable Business Recommendations

### 1. Retain VIP Customers

- Provide exclusive rewards.
- Offer early access to new products.
- Provide personalized offers.
- Give premium customer service.
- Focus on strategies that prevent high-value customers from leaving.

### 2. Reactivate At-Risk Customers

- Launch targeted re-engagement campaigns.
- Provide personalized discounts.
- Send reminder emails.
- Offer limited-time promotions.
- Encourage inactive customers to make another purchase.

### 3. Increase Regular Customer Value

- Use personalized product recommendations.
- Apply cross-selling strategies.
- Apply upselling strategies.
- Introduce loyalty rewards.
- Encourage customers to purchase more frequently.

### 4. Strengthen Customer Loyalty

- Introduce membership programs.
- Provide reward points.
- Offer benefits for repeat purchases.
- Encourage long-term customer relationships.

---

## Key Insights

- The largest customer segment consists of customers with moderate purchasing behaviour.
- At-risk customers show low recency, frequency, and spending.
- VIP customers are few in number but contribute very high value.
- Loyal customers purchase frequently and generate significant revenue.
- Different customer segments require different marketing strategies.

---

## Conclusion

RFM-based K-Means clustering provides a practical approach for understanding different customer behaviours.

By identifying **Regular, At-Risk, VIP, and Loyal customers**, businesses can develop targeted marketing strategies instead of using the same approach for every customer.

Customer segmentation can help businesses improve customer retention, increase customer value, strengthen loyalty, and focus marketing efforts on the most valuable customer groups.

---

## Project Files

- `Customer_Segmentation.ipynb` – Jupyter Notebook containing the complete analysis and clustering process.
- `README.md` – Project documentation.
- Charts/visualizations – Graphical representation of customer segments and analysis.

### Dataset Note

The original dataset is not included in this repository because its file size exceeds GitHub's upload limit. The analysis was performed using the original dataset locally.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- RFM Analysis
- Customer Behaviour Analysis
- K-Means Clustering
- Data Visualization
- Business Insights
- Actionable Recommendations


# Customer Segmentation using RFM Analysis and K-Means Clustering

Author: Sadha A
