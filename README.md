# MSCS_634: Lab 3-Clustering-Analysis-Using-K-Means-and-K-Medoids-Algorithms

## Overview
This lab demonstrates clustering analysis on the Wine Dataset using **K-Means** and **K-Medoids** algorithms. The goal was to explore the dataset, evaluate clustering performance, and compare both methods based on visualizations and evaluation metrics.

## Results
| Metric                       | K-Means        | K-Medoids       |
|------------------------------|----------------|-----------------|
| Silhouette Score             |   0.2849       | 0.2660          |
| Adjusted Rand Index (ARI)    |   0.8975       | 0.7263          |

**Insights:**
- **K-Means** performed slightly better in terms of cluster cohesion and alignment with actual wine classes.
- **K-Medoids** was more robust to outliers but had slightly lower evaluation metrics.

## Challenges
- Installing `scikit-learn-extra` for K-Medoids.
- Ensuring consistent feature scaling for clustering algorithms.
