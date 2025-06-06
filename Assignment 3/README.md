# Unsupervised Learning: PCA and K-Means from Scratch

-> Objective  
Implement Principal Component Analysis (PCA) and K-Means Clustering from scratch using only NumPy, Pandas, and Matplotlib.  
Apply these algorithms to the Iris dataset and visualize the results.

-> Dataset:Iris Dataset.csv

- Sepal length  
- Sepal width  
- Petal length  
- Petal width  
The target variable 'Species' is removed before applying unsupervised learning algorithms.

-> Preprocessing  
- The 'Species' column is saved separately for comparison.  
- Feature data is standardized using Z-score normalization.  
- Standardization helps in fair contribution of features to PCA and clustering.

-> PCA Implementation  
- Computed the covariance matrix of the standardized data  
- Calculated eigenvalues and eigenvectors  
- Sorted eigenvalues in descending order and selected the top 3  
- Projected the data onto the top 3 principal components  
- Visualized PCA with 3 scatter plots: PC1 vs PC2, PC1 vs PC3, PC2 vs PC3  
- Printed the top 3 eigenvalues

-> K-Means Implementation  
- Randomly initialized centroids for k = 3  
- Iteratively assigned data points to the closest centroid  
- Updated centroids based on current cluster members  
- Repeated until centroids converged or max iterations reached  
- Returned final labels and centroids

-> Visualizations  
- Scatter plot of K-Means clustering output  
- Scatter plot of actual species distribution  
- Compared clustering results with real labels visually

-> Technologies Used  
- Python 3.5+  
- NumPy  
- Pandas  
- Matplotlib

-> Project Structure  
- Python Notebook (.ipynb) containing all code and markdown explanations  
- All functions are written from scratch without using any prebuilt ML libraries  
- Notebook includes outputs, graphs, and final conclusion

-> Conclusion  
Successfully implemented PCA and K-Means Clustering from scratch  
Plotted and compared results to gain insights on clustering performance  
This project demonstrates the power of unsupervised learning and dimensionality reduction using foundational concepts only
