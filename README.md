# Wheat Grain Clustering

This repository contains an unsupervised learning project focused on clustering wheat grain data using **Agglomerative Hierarchical Clustering** and **K-Means Clustering**. The project aims to explore patterns in wheat grain geometrical properties.

## Dataset

The dataset used in this project is the **Seeds Dataset** (`seeds.csv`), which contains numerical measurements of wheat grains, quantifying their geometrical properties.

### Features:
- **Area** (float)
- **Perimeter** (float)
- **Compactness** (float)
- **Length** (float)
- **Width** (float)
- **Asymmetry Coefficient** (float)
- **Length Groove** (float)

## Objective

The purpose of this project is to:
- Implement **Agglomerative Hierarchical Clustering** and **K-Means Clustering** to identify patterns in the dataset.
- Understand how different clustering methods group the wheat grain samples based on their properties.
- Compare the performance and interpretability of hierarchical vs. K-means clustering.

## Implementation

- **Data Preprocessing:** Basic exploration of dataset features.
- **Clustering Methods:**  
  - **Agglomerative Hierarchical Clustering**: A bottom-up approach to build a hierarchy of clusters.
  - **K-Means Clustering**: A partition-based approach to group similar data points.
- **Evaluation:** Visualization and interpretation of clustering results.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/junaidraz1/hierarchical-kmeans-clustering.git
