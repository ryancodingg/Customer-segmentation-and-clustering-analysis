# Customer Segmentation and Clustering Analysis


This project focuses on customer segmentation using unsupervised machine learning techniques. The goal is to analyze customer data, identify distinct customer groups (clusters), and extract useful insights for business decision-making. The project includes data preprocessing, feature engineering, dimensionality reduction, and clustering using various algorithms like K-Means, DBSCAN, and K-Medoids. The performance of these models is evaluated using metrics such as silhouette score, Davies-Bouldin index, and Calinski-Harabasz index.

## Key Steps in the Project:
1. **Data Loading and Exploration**: The dataset is loaded, and basic exploratory data analysis (EDA) is performed to understand the structure of the data, identify missing values, and summarize key statistics.
2. **Data Preprocessing**: Features are standardized, and new engineered features are created. Principal Component Analysis (PCA) is applied for dimensionality reduction.
3. **Clustering**: Unsupervised clustering algorithms (K-Means, DBSCAN, K-Medoids) are used to segment the customers based on their characteristics such as age, annual income, and spending score.
4. **Model Evaluation**: The clustering models are evaluated using various clustering metrics including silhouette score, Calinski-Harabasz score, and Davies-Bouldin score.
5. **Visualization**: Visualizations such as scatter plots and heatmaps are used to explore relationships between features and to visualize the clustering results.

## Clustering Algorithms Used:
- **K-Means Clustering**: A centroid-based clustering algorithm used to partition customers into distinct groups based on their characteristics.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: A density-based clustering method that can identify clusters of varying shapes and sizes, and detect outliers (noise).
- **K-Medoids Clustering**: A variation of K-Means where the cluster centers are actual data points, providing a more robust alternative to K-Means.

## Evaluation Metrics:
- **Silhouette Score**: Measures how similar an object is to its own cluster compared to other clusters. A higher score indicates better-defined clusters.
- **Calinski-Harabasz Index**: Measures the ratio of the sum of between-cluster dispersion to within-cluster dispersion. Higher values indicate better-defined clusters.
- **Davies-Bouldin Index**: Measures the average similarity between each cluster and the cluster that is most similar to it. Lower values indicate better clustering.

## Visualizations:
- **PCA Visualization**: A scatter plot of the first two principal components of the dataset, colored by gender and clustering labels.
- **Clustering Results**: Visualizations of the clusters formed by K-Means, DBSCAN, and K-Medoids, with cluster centroids and evaluation metrics displayed.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
