# 📊 Rod Pump Dynamometer Card Shape Analysis

This project involves analyzing and clustering rod pump dynamometer cards to identify shape patterns indicative of specific mechanical behaviors, such as the 'freezing' pattern. We utilized techniques like Principal Component Analysis (PCA) and KMeans clustering to explore card shape similarities and outliers.

## 📂 Project Overview
The primary goal of this project is to process, clean, and cluster dynamometer card data to diagnose problems in oil well operations based on the card shapes. Dynamometer cards plot the stroke position (vertical displacement) of the pump versus the load on the pump, and their shapes are key indicators of operational issues.

### Key Steps:
1. **Data Preprocessing**: Cleaning and transforming raw data to prepare it for analysis.
2. **Dimensionality Reduction**: Using PCA to reduce the dimensions of the dataset.
3. **Clustering**: Applying KMeans to identify clusters of similar card shapes.
4. **Outlier Detection**: Identifying outliers and creating cleaner datasets.
5. **Shape Analysis**: Examining position profiles, load profiles, and clusters to diagnose patterns.

## 📊 Key Features:
- **Data Exploration**: Initial exploration of dynamometer card data, focusing on unique wells and card distributions.
- **Shape Profiling**: Generating visualizations of the first 10 card shapes, position profiles, and load profiles.
- **Outlier Detection**: Identifying and removing anomalous cards that distort the general analysis.
- **Clustering with PCA**: Reducing dimensionality with PCA and clustering similar card shapes using KMeans.
- **Pattern Detection**: Using KMeans to identify patterns such as the 'freezing' shape and others.

## 🛠️ Methods and Tools:
- **Python Libraries**: pandas, numpy, matplotlib, sklearn
- **Algorithms**:
  - Principal Component Analysis (PCA) for dimensionality reduction
  - KMeans clustering for identifying similar patterns
  - Affinity Propagation clustering for exploring clustering without predefined cluster counts
- **Visualization**: Matplotlib plots for card shapes, position/load profiles, and scatter plots for PCA components.

## 📈 Key Results:
- **Pattern Identification**: The analysis identified **44 cards** that closely resembled the 'freezing' pattern, using a combination of dimensional reduction and clustering.
- **Cluster Profiles**: Visualized the cluster center profiles to observe common behaviors in grouped card shapes.
- **Dimensionality Insights**: PCA highlighted key principal components that captured the variation in stroke effectiveness and pump behavior.

## 📁 Dataset:
The dataset consists of dynamometer card data collected from oil wells. The key columns represent position and load values across 200 points per card.
