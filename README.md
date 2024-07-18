# E-Commerce Customer Data Analysis

This project analyzes customer data from an e-commerce platform, focusing on clustering customers based on their search behaviors and visualizing various aspects of the data. The analysis involves clustering customers, calculating total searches, and visualizing customer counts and search behaviors across different clusters and genders.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Installation](#installation)
- [Analysis Process](#analysis-process)
- [Results](#results)

## Project Overview

This project aims to provide insights into customer behavior by analyzing their search data. The main steps include:

1. Clustering customers based on their search behaviors.
2. Calculating the total number of searches for each customer.
3. Visualizing the number of customers and their total searches across different clusters and genders.

## Data

The dataset used for this analysis contains the following columns:

- `Cluster`: Cluster ID of the customer.
- `Gender`: Gender of the customer.
- `Cust_ID`: Customer ID.
- `Orders`: Number of orders made by the customer.
- Various product columns representing search counts for different products.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- seaborn
- matplotlib
- scikit-learn

You can install the required libraries using:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Analysis Process

1. **Data Preparation**: Load and preprocess the customer data to handle missing values and ensure all columns are in the correct format.
   
2. **Clustering**: Use K-means clustering to group customers based on their search behaviors. The optimal number of clusters is determined using silhouette scores.

3. **Feature Engineering**: Calculate the total number of searches for each customer across various product categories.

4. **Visualization**: Create visualizations to understand the distribution of customers and their search behaviors across different clusters and genders. This includes bar plots and count plots.

## Results

The main results of this analysis include:

1. **No. of Customers and their Total Searches in "Cluster 0"**

   ![Customers count](https://github.com/PayalMh5/customer-segmentation/blob/main/Customers%20and%20their%20Total%20Searches.png)

2. **No. of Customers and their Total Searches in "Cluster 1"**

   ![Customers count](https://github.com/PayalMh5/customer-segmentation/blob/main/cluster1.png)

1. **No. of times customers searched the products and their past Orders**

   ![Customers count](https://github.com/PayalMh5/customer-segmentation/blob/main/Customers%20and%20their%20Total%20Searches.png)



   
