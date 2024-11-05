This commit includes a complete workflow for analyzing the BPS dataset:
- **Data Cleaning**: Removed null values, duplicates, and inconsistencies.
- **Data Transformation**: Standardized/normalized selected features for model readiness.
- **Exploratory Data Analysis (EDA)**:
  - *Univariate Analysis*: Summary statistics, distribution histograms, and boxplots.
  - *Multivariate Analysis*: Correlation heatmaps, pair plots, and cluster analysis.
- **Clustering**: KMeans clustering with optimized K using inertia analysis.
  - Tested several values for K.
  - Visualized clusters using scatterplot with PCA/t-SNE dimensionality reduction.

Optimized for data quality and visualization clarity.
