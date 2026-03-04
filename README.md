# Clustering Analysis: DBSCAN and Hierarchical Clustering

## 📌 Project Overview

This project demonstrates the implementation and comparison of two popular unsupervised machine learning clustering algorithms:

- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- **Hierarchical Clustering (Agglomerative Clustering)**

The goal of this project is to explore how these clustering algorithms group data points, visualize the clusters, and analyze their performance on the dataset.

---

## 📂 Project Structure

---

## 🧠 Algorithms Used

### 1️⃣ DBSCAN

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) groups together points that are closely packed and marks points in low-density regions as outliers.

**Key Parameters:**
- `eps` – Maximum distance between two samples
- `min_samples` – Minimum number of points required to form a dense region

**Advantages:**
- Detects clusters of arbitrary shape
- Identifies outliers automatically
- No need to specify number of clusters beforehand

---

### 2️⃣ Hierarchical Clustering

Hierarchical clustering builds a hierarchy of clusters using either:
- **Agglomerative approach (bottom-up)**
- **Divisive approach (top-down)**

In this project, Agglomerative clustering is used.

**Key Concepts:**
- Linkage criteria (ward, complete, average, single)
- Dendrogram visualization

**Advantages:**
- Easy to visualize using dendrograms
- Does not require pre-specifying number of clusters (can cut tree at different levels)

---

## 📊 Workflow

1. Import necessary libraries
2. Load and preprocess dataset
3. Apply DBSCAN clustering
4. Apply Hierarchical clustering
5. Visualize clustering results
6. Compare performance and behavior

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Scipy

---

## 📈 Results & Visualization

The notebook includes:
- Cluster visualizations
- Dendrogram plots
- Comparison of clustering behavior
- Analysis of outliers (for DBSCAN)

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
