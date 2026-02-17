# Enhancing PSO-Based Clustering using Autoencoders

![Research](https://img.shields.io/badge/Published-Springer-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Clustering-blue)
![Optimization](https://img.shields.io/badge/Optimization-PSO-orange)
![High Dimensional Data](https://img.shields.io/badge/Data-High%20Dimensional-purple)


This repository documents the published research:

**“Enhancing the Performance of PSO Algorithm for Clustering High Dimensional Data using Autoencoders.”**

This work was published in Springer.

📖 Read the full paper:
https://link.springer.com/chapter/10.1007/978-981-99-7817-5_38

DOI:
10.1007/978-981-99-7817-5_38

The research proposes a hybrid clustering framework that combines:

- Autoencoder-based dimensionality reduction
- Particle Swarm Optimization (PSO)
- K-Means clustering
- Cluster validity metrics (Davies–Bouldin Index & Silhouette Score)

---

## Problem Statement

Clustering high-dimensional datasets leads to:

- Increased computational complexity
- Poor separation between clusters
- Reduced optimization performance

This research improves clustering performance by:

1. Reducing dimensionality using an Autoencoder  
2. Determining optimal cluster count via Elbow Method  
3. Applying PSO to refine centroid optimization  
4. Comparing results against baseline K-Means  

---

## Research Contributions

- Integration of Autoencoder with PSO for clustering
- Performance evaluation on high-dimensional stock market data
- Comparison using Davies–Bouldin Index and Silhouette Score
- Execution time benchmarking
- Sector-wise cluster analysis

---

## Repository Structure

```
paper/                  Published research paper
methodology/            Algorithm explanation & math formulation
results/                Experimental outputs & performance tables
dataset_description.md  Dataset details
reproducibility_notes.md Experiment configuration notes
```

---

## Evaluation Metrics

- **Davies–Bouldin Index (DBI)** → Lower indicates better cluster separation
- **Silhouette Score** → Higher indicates better clustering quality
- **Execution Time Comparison**

---

## Disclaimer

This repository serves as a structured research documentation archive.  
The original experimental implementation was developed during the research phase and is not included here.

For full methodological and mathematical details, refer to the paper in the `paper/` directory.
