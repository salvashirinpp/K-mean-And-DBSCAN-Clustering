# ***Clustering Analysis — K-Means & DBSCAN***

This project demonstrates two major unsupervised learning techniques — K-Means and DBSCAN — using the Mall Customers dataset. It provides a clear comparison between centroid-based and density-based clustering approaches for customer segmentation.

## Overview

The notebook includes:

### **Data Preparation**

Importing the dataset

Checking for missing values and duplicates

Handling categorical features

Feature scaling for distance-based algorithms

### **K-Means Clustering**

Choosing optimal number of clusters using the Elbow Method

Training the K-Means model

Visualizing cluster separation

Interpreting segments based on spending score, income, etc.

### **DBSCAN Clustering**

Applying DBSCAN for density-based clustering

Tuning eps and min_samples

Detecting noise/outlier points

Visualizing non-linear cluster shapes

## Key Learnings

Difference between distance-based (K-Means) and density-based (DBSCAN) clustering

Importance of feature scaling

How hyperparameters (k, eps, min_samples) impact cluster formation

Practical segmentation of customer behavior

## Technologies Used

Python

NumPy & Pandas

Matplotlib & Seaborn

Scikit-learn
