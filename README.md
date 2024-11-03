# Market-Basket-Analysis-and-Customer-segmentation

# Market Basket Analysis and Customer Segmentation Dashboard

# Project Overview

This project applies Market Basket Analysis (MBA) and Customer Segmentation on supermarket transaction data to derive insights on customer purchase behaviors and identify frequent product associations. The project includes a Power BI dashboard to visualize the findings.

# Table of Contents
- Dataset Information
- Setup Instructions
- Project Workflow
- Insights and Findings
- Dashboard Overview
- Dataset Information
  
# Transaction Dataset
Columns: Member_number, Date, itemDescription, Number of Items, Month, Day of Week

Description: Each row contains customer transactions with items listed under itemDescription.

RFM Customer Segmentation
Columns: CustomerID, Recency, Frequency, Monetary, Cluster, Cluster_Label
Description: Classifies customers based on Recency, Frequency, and Monetary values.


# Project Workflow

1. Data Preprocessing and Exploratory Data Analysis (EDA)
Product Analysis: Identified top and least sold products.
Sales Trends: Examined sales by day, week, and month.

3. Market Basket Analysis (MBA)
Applied Apriori and FP-Growth algorithms to find frequent itemsets.
Generated association rules with metrics like support, confidence, and lift.

5. RFM Customer Segmentation
RFM Model: Segmented customers based on Recency, Frequency, and Monetary values.
Clustering: Used K-means to group customers into three segments:
Cluster 0: Recent Low-Spend Customers
Cluster 1: Less Engaged Customers
Cluster 2: Frequent & High-Value Customers

7. Dashboard Creation
Built in Power BI with visuals to display insights from MBA and Customer Segmentation.

# Insights and Findings
Product Affinities: Identified frequent product combinations, such as customers buying yogurt often buying whole milk.
Customer Segmentation: Gained insights into customer engagement levels, supporting marketing and inventory decisions.
Dashboard Overview
The Power BI dashboard visualizes project insights with the following components:

Customer Cluster Distribution (Pie Chart)
Top/Least Sold Products (Bar Charts)
Sales Trends (Line Chart)
Product Frequency (Bar Chart)
Key Metrics: Average Recency, Frequency, Monetary Value, and Basket Size per Customer
# Conclusion
This project demonstrates how Market Basket Analysis and Customer Segmentation can help businesses understand customer purchasing patterns, optimize marketing, and manage inventory effectively.

Feel free to explore the project, use the code, and adapt it to your needs
