# Data Analytics & Machine Learning on US Accidents Dataset

## 📌 Overview
This project focuses on **data analytics and machine learning** techniques applied to the **US Accidents Dataset**. It covers:
- **Data preprocessing** (handling missing values, feature selection, and outlier removal)
- **Clustering** (K-Means, DBSCAN)
- **Classification** (KNN, MLP for severity prediction)
- **Geospatial and statistical analysis**

## 📂 Project Structure
- 📁 `data/` → Contains preprocessed and cleaned datasets.
- 📁 `notebooks/` → Jupyter Notebooks with code implementations.
- 📁 `models/` → Trained ML models and evaluation results.
- 📁 `visualizations/` → Graphs, heatmaps, and scatter plots.

## 🔍 Key Steps
### 1️⃣ Data Preprocessing
- Handled missing values & reduced dataset size.
- Selected relevant features: **Latitude, Longitude, Weather, Visibility, Wind Speed**.
- Removed outliers using **Interquartile Range (IQR)**.

### 2️⃣ Clustering (K-Means, DBSCAN)
- Used **Elbow Method** to determine optimal clusters.
- Applied K-Means and DBSCAN clustering on accident severity and weather conditions.
- Evaluated clustering performance using **Silhouette Score**.

### 3️⃣ Classification (KNN, MLP)
- Built **K-Nearest Neighbors (KNN)** and **Multi-Layer Perceptron (MLP)** models.
- Used **Temperature, Visibility, Wind Chill** as key predictors.
- **Confusion Matrices & Performance Metrics**:
  - Accuracy: **97.47%**
  - F1 Score: **0.96**
- Identified **poor prediction for certain severity classes** due to data imbalance.

## 📊 Visualizations
- **Scatter plots** showing accident severity distribution across urban areas.
- **Heatmaps** to identify accident-prone regions.
- **Boxplots** comparing data before and after outlier removal.

## 🛠️ Technologies Used
- **Python, Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-learn, TensorFlow (MLP)**
- **Geospatial analysis (Folium, GeoPandas)**

## 🚀 Challenges & Learnings
- Removing **outliers** significantly reduced variance but also affected model generalization.
- Data imbalance caused poor performance on less frequent severity levels.
- **ML models struggled** to provide meaningful predictions beyond the dominant severity category.


