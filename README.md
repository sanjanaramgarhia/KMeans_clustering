KMeans Clustering on Customer Data

This project demonstrates how unsupervised machine learning can be applied to uncover hidden customer segments using the KMeans algorithm.

📌 Project Overview
The goal of this project is to perform customer segmentation by applying clustering techniques.

Key steps include:

Data cleaning & preprocessing

Feature scaling (StandardScaler, RobustScaler, MinMaxScaler)

Dimensionality reduction using Principal Component Analysis (PCA)

Determining the optimal number of clusters with the Elbow Method

Applying KMeans clustering and visualizing the results

⚙️ Technologies Used

Python 🐍
Pandas, NumPy → data manipulation
Matplotlib, Seaborn → visualization
Scikit-learn → scaling, PCA, clustering

🚀 Workflow

Data Preprocessing
Handled missing values (filled with mean)
Removed irrelevant columns (like CUST_ID)
Scaling
Compared multiple scalers: StandardScaler, RobustScaler, MinMaxScaler
Observed how scaling methods affect cluster formation
Dimensionality Reduction
Applied PCA
Retained ~90% variance with fewer components
Clustering
Used Elbow Method to find optimal k
Applied KMeans with 2 clusters
Visualized clusters along with centroids

📊 Results

Customers were segmented into two distinct groups.
Cluster visualization showed clear separation with centroids at the center of each cluster.
Scaling choice had a significant impact on how clusters were formed.

