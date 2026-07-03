# Customer Segmentation using K-Means Clustering

> A Machine Learning project that applies the **K-Means Clustering** algorithm to segment retail customers based on their purchasing behavior, enabling data-driven customer analysis and targeted marketing strategies.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)

---

## Overview

Customer segmentation is one of the most important applications of Unsupervised Machine Learning in business analytics.

This project leverages the **K-Means Clustering** algorithm to identify groups of customers with similar purchasing characteristics. By discovering natural customer segments, businesses can improve marketing campaigns, personalize customer experiences, and make informed strategic decisions.

The project follows a complete data science workflow—from data preprocessing and exploratory analysis to clustering, visualization, and interpretation of results.

---

## Problem Statement

Retail businesses often collect large amounts of customer data but struggle to transform it into actionable insights.

The objective of this project is to automatically group customers into meaningful clusters based on purchasing behavior, helping organizations understand different customer profiles without relying on predefined labels.

---

## Dataset

The project uses the **Mall Customer Dataset**, which contains demographic and spending information for customers.

### Features

| Feature | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1–100) | Spending behavior score assigned by the mall |

---

## Objectives

- Understand customer purchasing behavior
- Perform data preprocessing
- Identify the optimal number of customer clusters
- Apply the K-Means clustering algorithm
- Visualize customer segments
- Interpret business insights from each cluster

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
Customer-Segmentation-KMeans/
│
├── Mall_Customer.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
└── images/
```

---

## Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Feature Selection
6. Feature Scaling
7. Determine Optimal Clusters (Elbow Method)
8. Train K-Means Model
9. Customer Segmentation
10. Cluster Visualization
11. Business Insights

---

## K-Means Clustering

K-Means is an Unsupervised Machine Learning algorithm that partitions data into **K distinct clusters**.

Each customer is assigned to the nearest centroid, and the algorithm iteratively updates cluster centers until convergence.

This enables businesses to identify groups of customers with similar purchasing behavior without requiring labeled data.

---

## Model Evaluation

The project uses the **Elbow Method** to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

Visualization techniques are then used to interpret customer groups effectively.

---

## Business Value

The generated customer segments can support:

- Personalized Marketing Campaigns
- Customer Retention Strategies
- Product Recommendation Systems
- Loyalty Program Design
- Targeted Advertising
- Revenue Optimization

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Customer-Segmentation-KMeans.git
```

Navigate to the project directory

```bash
cd Customer-Segmentation-KMeans
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Results

The K-Means model successfully segments customers into meaningful groups based on purchasing behavior.

These clusters provide valuable insights that can be leveraged by businesses for strategic decision-making and customer-focused marketing initiatives.

---

## Future Enhancements

- Silhouette Score Evaluation
- Principal Component Analysis (PCA)
- Hierarchical Clustering Comparison
- DBSCAN Implementation
- Interactive Dashboard using Streamlit
- Real-Time Customer Segmentation API

---

## Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Unsupervised Machine Learning
- K-Means Clustering
- Business Analytics
- Scikit-learn
- Python Programming

---

## Author

**Dipanshu Shende**

Machine Learning Enthusiast


---

