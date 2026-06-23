# Customer-Segmentation-Analysis


## Project Overview

This project applies K-Means clustering to segment customers based on their purchasing behavior and demographic characteristics. The goal is to identify distinct customer groups that can be targeted with personalized marketing strategies, improving customer engagement and business performance.

## Objectives

* Analyze customer demographics and spending behavior.
* Identify meaningful customer segments using unsupervised machine learning.
* Visualize customer groups and purchasing patterns.
* Generate actionable business recommendations for targeted marketing campaigns.

## Dataset

The project uses the Mall Customers dataset containing:

* 200 customer records
* Customer demographics
* Annual income information
* Spending score metrics

### Features

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Workflow

### 1. Data Preprocessing

* Dataset inspection and validation
* Missing value analysis
* Feature selection
* Data scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Age distribution analysis
* Income distribution analysis
* Spending score analysis
* Customer demographic visualization

### 3. Customer Segmentation

* Applied K-Means clustering algorithm
* Determined the optimal number of clusters using the Elbow Method
* Segmented customers into five distinct groups

### 4. Visualization

* Cluster visualization using scatter plots
* Customer distribution analysis
* Segment comparison and interpretation

## Key Findings

### Cluster 0: Average Customers

* Moderate income and spending behavior
* Suitable for retention campaigns and bundle offers

### Cluster 1: VIP Customers

* High income and high spending behavior
* Ideal for premium products and loyalty programs

### Cluster 2: Young High-Spenders

* Younger customers with strong spending habits
* Suitable for targeted promotions and social media campaigns

### Cluster 3: Wealthy but Low-Spending Customers

* High income but low spending activity
* Potential targets for upselling and personalized offers

### Cluster 4: Budget Customers

* Lower income and lower spending behavior
* Responsive to discounts and value-focused promotions

## Results

The K-Means model successfully identified five customer segments with distinct behavioral patterns, enabling targeted marketing strategies and improved customer relationship management.

## Visualizations

### Elbow Method


### Customer Segmentation Plot




## Repository Structure

```text id="szwldm"
Customer-Segmentation-Analysis/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── visuals/
│
├── screenshots/
│   ├── elbow_method.png
│   └── customer_segments.png
│
├── models/
│
└── README.md
```


