# Customer-Segmentation
# Overview

This Jupyter Notebook performs Customer Segmentation using Principal Component Analysis (PCA) and Clustering techniques such as:

1.**K-Means Clustering**
   
2.**Agglomerative Clustering**
   
3.**DBSCAN (Density-Based Clustering)**

The goal is to identify distinct customer groups based on their purchasing behavior.

Dataset
The dataset consists of customer attributes such as income, spending, frequency, and other behavioral metrics.

The data is scaled before applying PCA to ensure optimal performance.

# Methodology

1.**Data Preprocessing**
Handling missing values
Standardizing the dataset (using StandardScaler)

2.**Dimensionality Reduction (PCA)**
PCA is applied to reduce high-dimensional data into 12 principal components.
A cumulative variance plot is used to determine the optimal number of components.

3.**Clustering Approaches**
K-Means Clustering (Elbow Method & Silhouette Score used for optimal k)
Agglomerative Clustering (Hierarchical approach)
DBSCAN (Density-based clustering for noise detection)

4.**Model Evaluation**
Silhouette Score is used to evaluate clustering performance.
Clusters are visualized using PCA, UMAP, and t-SNE projections.

# Results & Findings
The Silhouette Scores of different clustering techniques are compared.
Optimal Cluster Count is determined based on score trends.
A final customer segmentation model is presented with interpretable insights.

How to Run the Notebook
Install dependencies (if not already installed):

`
pip install pandas numpy matplotlib seaborn scikit-learn umap-learn
`

Open Jupyter Notebook:
`
jupyter notebook
`

Run all cells in the notebook to execute data processing, clustering, and visualization.`

# Future Improvements

1.Try different feature engineering techniques.

2.Use Deep Learning-based clustering (e.g., Autoencoders).

3.Implement customer lifetime value (CLV) prediction.
