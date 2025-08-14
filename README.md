# Clustering Projects: Music Genres & Wine Profiles

This repository contains two unsupervised machine learning projects demonstrating different clustering techniques — **Fuzzy C-Means** and **Agglomerative Hierarchical Clustering** — applied to real-world datasets.

---

## 1. Soft Clustering of Songs using Fuzzy C-Means

**Objective:**  
Cluster songs based on their acoustic features, allowing each song to belong to multiple genres with varying membership degrees.

**Dataset:**  
- **Source:** [Kaggle - Spotify Dataset](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db)  
- **Features:** Danceability, Energy, Loudness, Acousticness, Instrumentalness, Liveness, Valence, Tempo  

**Methodology:**  
- Data preprocessing and standardization  
- Applied **Fuzzy C-Means** clustering (m=2)  
- Interpreted membership degrees for each song  
- PCA-based visualization of clusters  

**Key Insight:**  
Soft clustering captures the overlap between musical genres, offering a more realistic classification than hard clustering.

---
