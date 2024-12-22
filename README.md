# Clustering Techniques on the Iris Dataset  

## Objective  

This project demonstrates the application of clustering techniques to the Iris dataset. We implement and compare two popular clustering algorithms: KMeans and Hierarchical clustering.  

## Dataset  

The Iris dataset consists of 150 samples of iris flowers with four features:  
- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  
 
## Key Components  

1. **Loading and Preprocessing**:   
   - Load the Iris dataset from the `sklearn` library.  
   - Drop the species column to focus on the features for clustering.  

2. **Clustering Algorithm Implementation**:  
   - **KMeans Clustering**:  
     - KMeans partitions the dataset into K clusters by minimizing variance within each cluster.  
     - Suitable for the Iris dataset because it has distinct clusters.  
     - Visualizes the resulting clusters.  
     
   - **Hierarchical Clustering**:  
     - Builds a hierarchy of clusters using an agglomerative approach.  
     - Suitable for exploring different cluster sizes and relationships.  
     - Visualizes the clusters and a dendrogram.  

3. **Visualizations**:   
   - Includes plots for both KMeans and Hierarchical clustering results to illustrate how each method clusters the data.  
