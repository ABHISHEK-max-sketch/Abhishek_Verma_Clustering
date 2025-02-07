# Clustering Analysis

This project applies clustering algorithms on the Iris dataset, evaluates their performance using different preprocessing techniques, and generates various outputs including results tables and heatmaps.

## Table of Contents

1. [Overview](#overview)
2. [Preprocessing Methods](#preprocessing-methods)
3. [Clustering Algorithms](#clustering-algorithms)
4. [Metrics](#metrics)
5. [Results](#results)
6. [Steps](#steps)
7. [Images](#images)

## Overview

In this project, we explore the performance of three clustering algorithms: **K-Means**, **Hierarchical**, and **Mean-Shift**. The Iris dataset is preprocessed using different methods such as standard scaling, min-max scaling, PCA, and a combination of transformations. The clustering performance is evaluated using three metrics:

- **Silhouette Score**
- **Calinski-Harabasz Index**
- **Davies-Bouldin Index**

Results are stored in tables and visualized as heatmaps. The tables and heatmaps are saved as images and CSV files.

## Preprocessing Methods

The following preprocessing techniques are applied to the Iris dataset:

1. **No Data Processing**: Raw dataset.
2. **Using Normalization**: Min-max scaling.
3. **Using Transformation**: Standard scaling.
4. **Using PCA**: Principal component analysis (PCA) is applied to reduce dimensionality.
5. **Using Transform + Normalize (T+N)**: Combination of standard scaling and normalization.
6. **Using T+N+PCA**: Combination of transform, normalize, and PCA.

## Clustering Algorithms

We apply the following clustering algorithms:

- **K-Means**: A centroid-based clustering algorithm.
- **Hierarchical**: A tree-based clustering algorithm.
- **Mean-Shift**: A density-based clustering algorithm.

The number of clusters tested includes 3, 4, and 5 for each preprocessing method.

## Metrics

The following clustering metrics are calculated for each clustering algorithm:

1. **Silhouette Score**: Measures how similar an object is to its own cluster compared to other clusters.
2. **Calinski-Harabasz Index**: Measures the ratio of the sum of between-cluster dispersion to within-cluster dispersion.
3. **Davies-Bouldin Index**: Measures the average similarity ratio of each cluster to its most similar cluster.

## Results

The results are saved in the following files:

- **CSV Files**: Results for each clustering algorithm saved as `results_kmeans.csv`, `results_hierarchical.csv`, and `results_meanshift.csv`.
- **PNG Files**: Tables and heatmaps of the results saved as images:

    - `table_kmeans.png`
    - `table_hierarchical.png`
    - `table_meanshift.png`
    - `heatmap_kmeans.png`
    - `heatmap_hierarchical.png`
    - `heatmap_meanshift.png`

## Steps

- **Step 1**: Load the Iris dataset.
- **Step 2**: Preprocess the data using different methods.
- **Step 3**: Apply clustering algorithms (K-Means, Hierarchical, Mean-Shift).
- **Step 4**: Compute the clustering metrics (Silhouette Score, Calinski-Harabasz, Davies-Bouldin).
- **Step 5**: Save results in tables and images.
- **Step 6**: Visualize results using heatmaps.

## Images

Below are the results for each clustering algorithm:

1. **K-Means Clustering Results Table**

![table_kmeans](https://github.com/user-attachments/assets/4d95cfc5-be8e-4309-9483-a11327449b48)



2. **Hierarchical Clustering Results Table**

![table_hierarchical](https://github.com/user-attachments/assets/615e4e69-4fc1-4133-b944-31e402aaa8b9)


3. **Mean-Shift Clustering Results Table**

![table_meanshift](https://github.com/user-attachments/assets/d2e62a2e-78cf-4aa4-8ef9-9eee703bb2b0)


4. **K-Means Clustering Heatmap**

 ![heatmap_kmeans](https://github.com/user-attachments/assets/4e09891f-7665-48d5-9a57-956b057a8057)


5. **Hierarchical Clustering Heatmap**

![heatmap_hierarchical](https://github.com/user-attachments/assets/6f335c99-9eb8-49a5-b2fa-52f27d612bbb)


6. **Mean-Shift Clustering Heatmap**

  ![heatmap_meanshift](https://github.com/user-attachments/assets/646c4320-5c77-4074-8f39-bff6ab6e6787)


## Conclusion

This project demonstrates the application of clustering algorithms on the Iris dataset with various preprocessing techniques. The evaluation of clustering performance is done using multiple metrics, and the results are visualized using tables and heatmaps.
