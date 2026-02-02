**Unsupervised Learning with the Iris Dataset**
**Objective**

The objective of this assignment is to understand unsupervised learning by grouping similar flowers from the Iris dataset using K-Means clustering. The model finds patterns in the data without using flower names (species).

Dataset

The Iris dataset contains flower measurements with the following features:

-Sepal Length

-Sepal Width

-Petal Length

-Petal Width

The Species column is removed because unsupervised learning does not require labeled data.
**Tools Used**

-Python

-Pandas

-NumPy

-Matplotlib

-Scikit-learn

**Steps Followed in the Assignment**
1. Importing Libraries

Pandas is imported to handle the dataset. Other libraries are used for scaling the data, applying clustering, and creating plots.

2. Loading the Data

The dataset is loaded using pd.read_csv() and stored in a pandas DataFrame. This allows easy viewing and manipulation of the data.

3. Exploring the Data

The data is explored by:

Viewing the first few rows

Checking the number of rows and columns

Viewing summary statistics

This helps to understand the structure and range of the data.

4. Visualizing the Data

Scatter plots are created to examine relationships between features:

Sepal Length vs Sepal Width

Petal Length vs Petal Width

These plots help identify possible natural groupings.

5. Feature Scaling

All features are scaled using StandardScaler so that they are on the same scale. This is important because K-Means clustering uses distance to group data points.

6. Applying K-Means Clustering

K-Means clustering is applied using three clusters. Each data point is assigned to a cluster based on similarity.

7. Cluster Centers

Cluster centers (centroids) are calculated. A centroid represents the average position of all points in a cluster.

8. Cluster Visualization

Clusters are visualized using a scatter plot of Petal Length vs Petal Width. Different colors represent different clusters, and centroids are marked on the plot.

9. Elbow Method

The elbow method is used to test different numbers of clusters (k = 1 to 10). The point where the graph bends helps determine a good number of clusters.

**Key Observations**

Petal features show clearer groupings

Three clusters seem reasonable

Some overlap between clusters is expected

**Conclusion**

This assignment demonstrates how unsupervised learning can be used to find patterns in data without labels. K-Means clustering successfully grouped similar flowers in the Iris dataset.
