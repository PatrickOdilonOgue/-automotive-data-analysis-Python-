# -automotive-data-analysis-Python-

Prospect Auto – Unsupervised Learning Approach
This project explores the application of unsupervised learning techniques to automatically identify and group vehicles based on their geometric features. Utilizing a dataset of vehicle silhouettes and 18 extracted geometric attributes, the goal is to discover natural clusters within the data without relying on predefined class labels like 'Bus', 'Car', or 'Van'.

Key Features and Analysis:

Data Preprocessing: Handling of missing values and duplicates, followed by robust scaling of features.
Dimensionality Reduction: Application of PCA to reduce the 18 features to a more manageable set while retaining significant variance.
Noise Reduction: Using DBSCAN with optimized hyperparameters to identify and remove outliers.
Clustering: Implementing K-Means clustering to group the cleaned, reduced data.
Cluster Evaluation: Utilizing the Elbow Method and Silhouette Score to determine the optimal number of clusters.
Visualization: Visualizing the clusters in 2D using t-SNE to understand their separation and structure.
Feature Analysis: Examining the distribution of key principal components within each cluster to understand which features drive the clustering.
External Validation (Optional): Comparing the unsupervised clusters to the original vehicle classes using the Adjusted Rand Index (ARI).
Findings:

The project successfully identified distinct clusters based on geometric features. However, the low Adjusted Rand Index suggests that these naturally occurring clusters do not strongly align with the traditional vehicle classifications. This indicates that the geometric features capture nuances in vehicle shape beyond simple class distinctions.

Future Work:

Explore alternative clustering algorithms (e.g., Hierarchical Clustering, Gaussian Mixture Models).
Further optimize model hyperparameters.
Incorporate additional relevant features.
Re-evaluate the dimensionality reduction approach.
This project provides insights into the underlying structure of vehicle shapes and demonstrates an unsupervised approach to identifying groupings within complex geometric data.
