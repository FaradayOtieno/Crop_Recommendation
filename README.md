# 🌱 Uncovering Crop Suitability with Machine Learning: PCA + KMeans Clustering Approach


This project explores how machine learning can help recommend suitable crops based on soil and weather conditions. Using **unsupervised clustering (KMeans)** and **PCA visualization**, we extract actionable insights on crop suitability across environmental profiles.

## 📌 Project Highlights

- Performed **KMeans clustering** on crop environment data
- Visualized clusters in **2D PCA space**
- Interpreted clusters by **dominant crops and feature deviations**
- Identified crop suitability zones based on real data

## 🧪 Tech Stack

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

## 📊 Dataset Features

- `N`, `P`, `K`: Macronutrients in soil
- `temperature`, `humidity`
- `ph`: Soil acidity
- `rainfall`: Annual rainfall in mm
- `label`: Crop name

## 🧠 ML Pipeline

1. Data preprocessing and exploration
2. Classification (supervised learning baseline)
3. KMeans clustering (n=4)
4. Cluster interpretation using feature means
5. PCA for dimensionality reduction and visualization
6. Cluster-crop relationship analysis

## 📈 Results

- Achieved ~99.4% accuracy with classification
- Identified 4 distinct environmental clusters
- Mapped dominant crops to each cluster based on suitability

## 🔍 Example Insight

> Cluster 0 → Low NPK, moderate humidity/rainfall → Best crops: chickpea, blackgram  
> Cluster 1 → High N, warm and humid → Best crops: cotton, muskmelon  
> Cluster 2 → High rainfall → Best crops: rice, coconut  
> Cluster 3 → Acidic soil, humid → Best crops: grapes, apple

## 📄 License

MIT

---
