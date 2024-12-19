# Mall Customer Segmentation

This repository contains a project for analyzing mall customer data to segment customers into distinct groups. The segmentation helps businesses target marketing strategies and enhance customer experiences.

## Project Overview

Customer segmentation categorizes a customer base into meaningful groups based on shared characteristics. This project:

- Analyzes mall customer data using exploratory data analysis (EDA).
- Applies clustering techniques to identify customer segments.
- Provides actionable insights for marketing and customer relationship management.

## Dataset

The dataset includes:

- **CustomerID**: Unique customer identifier.
- **Gender**: Male or Female.
- **Age**: Customer age.
- **Annual Income (k$)**: Estimated yearly income (in thousands).
- **Spending Score (1-100)**: Spending behavior scored from 1 to 100.

## Key Steps

### 1. Exploratory Data Analysis (EDA)
- Visualized distributions of features like **Age**, **Annual Income**, and **Spending Score** using histograms.
- Identified outliers using boxplots for features.
- Explored pairwise relationships with pair plots.

### 2. Clustering
- Preprocessed the data by scaling features.
- Used **K-Means Clustering** to segment customers:
  - Determined the optimal number of clusters (6) using silhouette scores and the elbow method.
  - Analyzed cluster characteristics to interpret segmentation.

### 3. Visualizations
- Visualized customer segments in 2D and 3D scatter plots.
- Compared clusters using feature distributions to understand group characteristics.

### 4. Insights
- Segmented customers into **6 distinct groups**:
  1. **Cluster 1**: High-income, high-spending individuals.
  2. **Cluster 2**: Low-income, low-spending individuals.
  3. **Cluster 3**: Middle-aged, moderate-income, moderate-spending customers.
  4. **Cluster 4**: Younger customers with varied spending patterns.
  5. **Cluster 5**: High-income individuals with conservative spending habits.
  6. **Cluster 6**: Budget-conscious younger customers.

## Key Results

- **Optimal Clusters**: 6 clusters were identified using K-Means clustering, with clear group characteristics.
- **Cluster Profiles**:
  - Highlighted variations in age, income, and spending behavior.

## Tools and Libraries

- **Data Analysis**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Clustering**: `scikit-learn`
- **Interactive Plots**: `plotly` (optional)

## How to Use

1. Clone the repository:
   ```bash
   git clone (https://github.com/abdelrahman-ehab/mall-customer-segmentation)
