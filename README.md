# Clustering Assignment

## Overview
This assignment explores various **clustering algorithms** using synthetic and real-world datasets. It covers **K-Means, DBSCAN, and Agglomerative Clustering** while using techniques like **PCA and t-SNE** for dimensionality reduction and **silhouette scores** for evaluation.

## Datasets Used
- **Synthetic Datasets**: `make_blobs`, `make_circles`, `make_moons`
- **Real Datasets**: Iris, Wine, Digits, Breast Cancer

## Implemented Clustering Techniques
- **K-Means Clustering**
- **DBSCAN (Density-Based Spatial Clustering)**
- **Agglomerative Hierarchical Clustering**

## Key Tasks
1. **K-Means Clustering**
   - Apply to synthetic and real datasets.
   - Use Elbow Method and Silhouette Score for evaluation.
   - Visualize cluster assignments using scatter plots and pair plots.

2. **DBSCAN Clustering**
   - Identify noise and clusters in non-linearly separable data.
   - Compare results with K-Means.
   - Visualize using decision boundaries.

3. **Agglomerative Clustering**
   - Apply different linkage criteria: Single, Complete, Average, Ward’s.
   - Visualize results using scatter plots and dendrograms.

4. **Dimensionality Reduction**
   - Use PCA and t-SNE to reduce dataset dimensions.
   - Apply clustering algorithms to lower-dimensional data.

## Requirements
Install dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
