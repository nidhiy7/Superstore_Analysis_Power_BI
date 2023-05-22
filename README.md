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

## Customer Segmentation
RFM Analysis: This technique segments customers based on three key metrics:

1)Recency: Number of days since the customer's last purchase.
2)Frequency: Number of purchases made by the customer.
3)Monetary Value: Total amount spent by the customer.
- Calculate RFM Scores: Calculate the RFM scores for each customer by assigning a score to each of the three metrics. For example, customers who made a purchase recently would receive a high recency score, while those who made frequent purchases would receive a high frequency score. The monetary value score can be based on the total amount spent.

- Customer Segmentation: Segment customers into groups based on their RFM scores. Typically, customers are divided into segments based on combinations of high or low scores. For example, "Best Customers" may have high scores across all three metrics, while "At Risk" customers may have low recency and frequency scores but a high monetary value score.

- K-means Clustering: Use the K-means clustering algorithm to group similar customers together based on their RFM scores. This unsupervised machine learning algorithm partitions the customers into clusters based on their similarities. The optimal number of clusters is determined using techniques like the elbow method.

- Assign Customers to Clusters: Assign each customer to a specific cluster based on their RFM scores and the clusters identified by the K-means algorithm. This provides a way to understand and target different customer segments effectively.

By performing RFM Analysis and applying K-means clustering, you can gain insights into customer behavior, identify valuable customer segments, and tailor marketing and retention strategies accordingly.

## Analysis 
1)Regional Performance: The Central region has the highest total sales and profit, while the South region has the lowest.

2)Profit Margin by Product Category: Furniture has the lowest profit margin among all product categories, while Technology has the highest profit margin.

3)Average Order Value by Order Method: Orders placed via the phone have a higher average order value compared to online or mail orders.

4)Average Order Value by Customer Segment: Customers in the Home Office segment have the highest average order value, while those in the Consumer segment have the lowest.

5)Seasonal Sales and Profit: Sales and profit tend to be higher in the second half of the year (July to December) compared to the first half (January to June).

6)Correlation between Sales and Profit: There is a positive correlation between sales and profit, but the strength of the correlation varies by region.

7)Top-Performing Products: The top-performing products in terms of sales and profit are concentrated in the Technology and Office Supplies categories.

8)Customer Behavior: Some customers consistently generate high sales and profit, while others make occasional purchases with lower values.

9)Sub-Category Profit Margins: Certain sub-categories, such as Machines and Tables, consistently have low profit margins, indicating a need to re-evaluate pricing or sourcing strategies for those products.

10)Customer Segmentation: The analysis includes customer segmentation using RFM (Recency, Frequency, Monetary) scores. The Loyal customer segment demonstrates the highest purchasing frequency and generates the most profit, while the Churned customer segment has the lowest RFM scores and generates the least profit. The focus should be on retaining Loyal customers and re-engaging Churned customers.

## Conclusion 
This project report provides an in-depth analysis of sales and profit for Superstore. The visualizations offer clear insights into trends and patterns, enabling data-driven decision-making. The customer segmentation using RFM Analysis and K-means clustering enables targeted marketing strategies for different customer groups.




