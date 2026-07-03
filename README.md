# Customer Segmentation Analysis using K-Means Clustering

A machine learning project that applies the **K-Means Clustering** algorithm to segment retail customers based on purchasing behavior. This project demonstrates a complete unsupervised learning workflow, from data preprocessing and exploratory data analysis to customer segmentation and business insight generation.

---

## Overview

Customer segmentation is one of the most valuable applications of unsupervised machine learning in retail analytics. By identifying customers with similar purchasing characteristics, businesses can design personalized marketing campaigns, improve customer retention, and make data-driven strategic decisions.

In this project, the **K-Means Clustering** algorithm is implemented using the **Mall Customers Dataset** to discover meaningful customer groups based on annual income and spending score.

---

## Problem Statement

Retail businesses often collect large volumes of customer data but struggle to transform it into actionable insights.

The objective of this project is to automatically group customers with similar purchasing behaviors using the K-Means Clustering algorithm, enabling businesses to better understand customer segments and optimize marketing strategies.

---

## Dataset

**Dataset:** Mall Customers Dataset

The dataset contains customer demographic and spending information collected from a retail shopping mall.

| Feature | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Spending behavior score assigned by the mall |

---

## Project Objectives

- Explore customer purchasing behavior
- Perform exploratory data analysis (EDA)
- Select relevant features for clustering
- Determine the optimal number of clusters using the Elbow Method
- Train a K-Means Clustering model
- Visualize customer segments
- Generate business insights from customer groups

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```
SCT_ML_2/
│
├── Mall_Customer.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

## Project Workflow

### 1. Data Collection

- Load the Mall Customers Dataset

### 2. Data Exploration

- Understand dataset structure
- Check missing values
- Explore feature distributions

### 3. Data Preprocessing

- Select relevant features
- Prepare data for clustering

### 4. Model Development

- Apply the Elbow Method
- Determine the optimal value of K
- Train the K-Means Clustering model

### 5. Customer Segmentation

- Assign customers to clusters
- Visualize customer groups

### 6. Business Insights

- Analyze characteristics of each customer segment
- Interpret customer purchasing patterns

---

## K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to partition unlabeled data into K distinct clusters.

The algorithm works by:

- Initializing cluster centroids
- Assigning each customer to the nearest centroid
- Updating centroid locations
- Repeating the process until convergence

This approach enables businesses to discover natural customer groups without predefined labels.

---

## Model Evaluation

The optimal number of clusters is determined using the **Elbow Method**, which analyzes the Within-Cluster Sum of Squares (WCSS).

The resulting customer clusters are visualized to evaluate segmentation quality and support business interpretation.

---

## Results

The K-Means model successfully identifies distinct customer segments based on annual income and spending score.

These customer groups can support:

- Personalized Marketing
- Customer Retention
- Product Recommendation
- Targeted Advertising
- Loyalty Program Design
- Revenue Optimization

---

## Installation

Clone the repository:

```bash
git clone https://github.com/dipanshushende/SCT_ML_2.git
```

Navigate to the project directory:

```bash
cd SCT_ML_2
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Mall_Customer.ipynb
```

Run all notebook cells sequentially.

---

## Future Enhancements

- Silhouette Score Evaluation
- Principal Component Analysis (PCA)
- Hierarchical Clustering
- DBSCAN Clustering
- Interactive Dashboard using Streamlit
- Deployment using Flask

---

## Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Visualization
- Unsupervised Machine Learning
- K-Means Clustering
- Business Analytics
- Python Programming
- Scikit-learn

---

## Repository

**GitHub Repository**

https://github.com/dipanshushende/SCT_ML_2

---

## Author

**Dipanshu Shende**

Machine Learning Enthusiast | Python Developer | Data Science Learner

GitHub: https://github.com/dipanshushende

---


## Acknowledgements

- SkillCraft Technology – Machine Learning Internship
- Scikit-learn Documentation
- Mall Customer Dataset



---

## License

This project is developed for educational purposes as part of the **SkillCraft Technology Machine Learning Internship**.

---

### ⭐ If you found this project useful, consider giving it a star!
