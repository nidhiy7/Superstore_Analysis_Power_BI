# Superstore_Analysis_Power_BI-Dashboard

# Introduction
This project focuses on analyzing the sales and profit data of the  company "Superstore" and includes customer segmentation using RFM Analysis and K-means clustering. The dataset used is a sample dataset provided by Superstore. The main objectives of the project are to examine the sales and profit performance of Superstore and to identify different customer segments based on their purchasing behavior.Overall, this report provides a comprehensive analysis of Superstore's sales and profit data, incorporating customer segmentation techniques to gain valuable insights into customer behavior and preferences.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Power BI

## Data Source
Dataset: https://www.kaggle.com/datasets/juhi1994/superstore

## Project Description
This project is divided into two main parts: Visualization and Analysis.
## Visualization 
1)Sales and Profit Trend Over Time: Visualizing the trend of sales and profit over time using line charts or area charts.

2)Sales and Profit by Category and Sub-Category: Displaying sales and profit values for different product categories and sub-categories using bar charts or column charts.

3)Sales and Profit by Region: Visualizing sales and profit values across different regions using a geographic map or a filled map.

4)Interactive Filters: Incorporating interactive filters such as slicers or drop-down menus to enable users to filter data by year, customer, and region, allowing for more focused and personalized analysis.

By utilizing these visualizations and interactive filters, the Power BI project aims to provide insights into the sales and profit trends, category/sub-category performance, and regional analysis, allowing for a comprehensive understanding of the data and facilitating data-driven decision making.

## Analysis
RFM Analysis: This technique segments customers based on three key metrics:

1)Recency: Number of days since the customer's last purchase.
2)Frequency: Number of purchases made by the customer.
3)Monetary Value: Total amount spent by the customer.
- Calculate RFM Scores: Calculate the RFM scores for each customer by assigning a score to each of the three metrics. For example, customers who made a purchase recently would receive a high recency score, while those who made frequent purchases would receive a high frequency score. The monetary value score can be based on the total amount spent.

- Customer Segmentation: Segment customers into groups based on their RFM scores. Typically, customers are divided into segments based on combinations of high or low scores. For example, "Best Customers" may have high scores across all three metrics, while "At Risk" customers may have low recency and frequency scores but a high monetary value score.

- K-means Clustering: Use the K-means clustering algorithm to group similar customers together based on their RFM scores. This unsupervised machine learning algorithm partitions the customers into clusters based on their similarities. The optimal number of clusters is determined using techniques like the elbow method.

- Assign Customers to Clusters: Assign each customer to a specific cluster based on their RFM scores and the clusters identified by the K-means algorithm. This provides a way to understand and target different customer segments effectively.

By performing RFM Analysis and applying K-means clustering, you can gain insights into customer behavior, identify valuable customer segments, and tailor marketing and retention strategies accordingly.


