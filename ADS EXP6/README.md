# ADS EXP 6 - Outlier Detection

## Introduction

Outlier detection involves identifying data points that significantly deviate from the norm or expected patterns within a dataset. These outliers, anomalies, or exceptions often provide valuable insights across various domains, ranging from healthcare to manufacturing. For example, anomalies detected in medical imaging scans could indicate potential health issues, while abnormal sensor readings in manufacturing plants may signify equipment malfunction.

## Methods

Outlier detection methods typically fall into two categories: distance-based and density-based approaches.

### Distance-Based Methods

Distance-based methods identify outliers based on their distance from other data points. Common techniques include:

- **k-Nearest Neighbors (kNN)**: Assigns an outlier score based on the distance to its k-nearest neighbors.
- **Local Outlier Factor (LOF)**: Measures the local density deviation of a data point with respect to its neighbors.

### Density-Based Methods

Density-based methods focus on identifying regions of high and low density within the dataset. Key techniques include:

- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: Clusters dense regions while marking points in low-density regions as outliers.
- **Isolation Forest**: Constructs isolation trees to isolate outliers more efficiently than traditional methods.
