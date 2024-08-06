# Customer-Segmentation-using-K-Means-Clustering

This project demonstrates customer segmentation using the K-Means clustering algorithm on the Mall Customers dataset. The objective is to identify distinct customer groups based on their annual income and spending scores.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)

## Introduction
Customer segmentation is a powerful technique used in marketing to divide a customer base into distinct groups that share similar characteristics. This project leverages the K-Means clustering algorithm to segment customers, allowing for targeted marketing strategies and personalized customer experiences.

## Dataset
The dataset used in this project is the Mall Customers dataset, which contains information about customers' annual income and spending scores.
Link to the dataset: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Features:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Installation
To run this project, ensure you have Python installed along with the required libraries. You can install the necessary libraries using the `requirements.txt` file.

###Exploratory Data Analysis
- Loading and inspecting the dataset
- Checking for missing values
- Visualizing the data to understand distributions and patterns

###Model Building
Steps:
- Import the necessary libraries
- Load the dataset
- Select features for clustering (Annual Income and Spending Score)
- Use the Elbow Method to find the optimal number of clusters
- Build the K-Means model with the optimal number of clusters
- Visualize the clusters and their centroids

###Results
The clustering results in five distinct customer segments:

- Cluster 1: High earners, low spenders
- Cluster 2: Average earners and spenders
- Cluster 3: High earners, high spenders (Target Segment)
- Cluster 4: Low earners, high spenders
- Cluster 5: Low earners, low spenders

###Conclusion
This project demonstrates how K-Means clustering can be effectively used for customer segmentation. The insights derived can help businesses in targeted marketing and personalized customer engagement strategies.
