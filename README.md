# 🚑 Optimal ambulance positioning for road accidents with deep embedded clustering
This project presents a deep learning-based framework for identifying **optimal ambulance positioning** in urban areas to improve emergency response times. By analyzing real-time accident, road segment, and weather data from Nairobi, it leverages **Deep Embedded Clustering (DEC)** and **Cat2Vec embeddings** to predict accident hotspots and suggest strategic ambulance deployment locations.

---

## 📌 Key Features

- 📊 Real-time analysis of traffic accidents, road conditions, and weather data
- 🧠 Deep Embedded Clustering (DEC) for precise hotspot detection
- 🧬 Cat2Vec: Deep embeddings for high-cardinality categorical variables
- 🗺️ Predicts coordinates for optimal ambulance positions in a city
- 📈 Achieves 95% clustering accuracy using K-Fold cross-validation
- ✅ Outperforms traditional clustering algorithms (K-Means, GMM, Agglomerative)

---

## 🧠 Techniques Used

- **Deep Embedded Clustering (DEC)** with autoencoders
- **Cat2Vec**: Neural network embeddings for categorical data
- **Exploratory Data Analysis (EDA)** to extract accident patterns
- **Custom distance scoring** for real-world validation of cluster centroids
- **Evaluation Metrics**: Silhouette Score, Calinski-Harabasz Index, Davies-Bouldin Index, and a novel distance-based metric

---

This project is based on my published research. 📄 [Read the full paper here](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10147832).
 
