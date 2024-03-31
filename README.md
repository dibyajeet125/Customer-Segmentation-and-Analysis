# Customer-Segmentation
Customer Segmentation by K-Means Clustering with the help of olist dataset. 

About the Dataset

Brazilian E-Commerce Public Dataset by Olist

This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

Our main aim is to do Customer Segmentation by K-Means Clustering with the help of the dataset. We first did some Exploratory Data Analysis (EDA) using Data Warehouse operations like slicing, dicing, roll-up, drill-down and pivot. Then we move to our clustering part like first we did feature engineering by adding various new features like RFM, Product Diversity, Product Based Features, Geographic features, Behavioral features, Seasonality and Trends then we move to correlation analysis for identifying the relationship between the features, then we did feature scaling for normalizing the data. Then next we did dimensionality reduction using PCA to remove the correlated features. Then we finally did clustering using K-Means by identifying our cluster number by elbow method and silhouette method. Then after clustering we did evaluations, analysis and profiling of our clusters.

olist_geolocation_dataset.csv link:
https://www.kaggle.com/code/mauriciovellasquez/e-commerce-data-analysis/input?select=olist_geolocation_dataset.csv
