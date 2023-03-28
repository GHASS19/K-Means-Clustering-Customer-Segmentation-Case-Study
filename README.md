# K-Means Clustering Customer Segmentation

### In this case study, you will implement the K-Means clustering algorithm, find the value for K using the Elbow method, the Silhouette method, and the Gap statistic, and visualize the clusters with Principal Components Analysis (PCA). You'll use real data containing information on marketing newsletters and email campaigns, as transaction-level data from customers.


![image](https://user-images.githubusercontent.com/86930309/228121420-cf4cdbe6-3116-4dac-81b3-d9a90c8cd234.png)

## Structure of the Mini-Project:

## 1. Sourcing and loading

### Load the data

The dataset contains information on marketing newsletters/e-mail campaigns (e-mail offers sent to customers) and transaction level data from customers. The transactional data shows which offer customers responded to, and what the customer ended up buying. The data is presented as an Excel workbook containing two worksheets. Each worksheet contains a different dataset.

### Explore the data

We see that the first dataset contains information about each offer such as the month it is in effect and several attributes about the wine that the offer refers to: the variety, minimum quantity, discount, country of origin and whether or not it is past peak.

The second dataset in the second worksheet contains transactional data. It contains which offer each customer responded to.

## 2. Cleaning, transforming and visualizing

### Data Wrangling: Exercise Set 1

- Creating a matrix with a binary indicator for whether they responded to a given offer
- Ensure that in doing so, NAN values are dealt with appropriately

## 3. Modelling

### K-Means clustering: Exercise Sets 2 and 3

- Choosing K: The Elbow method. The elbow method suggests we use 4 clusters.

- Choosing K: The Silhouette method. The average silhouette score suggests that we use 5 clusters.

- Choosing K: The Gap statistic method

- Visualizing clusters with PCA: Exercise Sets 4 and 5

In this graph we have three different clusters of customers who exhibit certain similar purchasing behavior using PCA to reduce the vast amount of variables into smaller ones.

![image](https://user-images.githubusercontent.com/86930309/228367832-9ff89d13-86f1-41c3-ae8c-ba610a42159f.png)

This is the red cluster with the count of the different offer id that a customer responed to:

![image](https://user-images.githubusercontent.com/86930309/228368441-db0aff4d-d809-4597-8eeb-1ba85fe26fae.png)

This is the green cluster withe offer id:

![image](https://user-images.githubusercontent.com/86930309/228368516-4cae3d03-ccef-4331-9e40-8a5ae3fcf751.png)

Lastly we have the blue cluster:

![image](https://user-images.githubusercontent.com/86930309/228368544-570b44d4-614a-4713-a453-a040279463cd.png)

## 4. Conclusions and next steps

- Conclusions

The Elbow Sum-of-Squares Method suggests we use a cluster of four. Using the silhouette method that recommends using
a cluster of 5 since it has the highest average silhoutte. The PCA displays that four, (maybe five) is the optimal dimensions for this dataset. The PCA expresses that the first four to five components explain a majority of the variance. Since these methods suggest four or five i would test both of those values out to see which is a better fit for the data.

- Other clustering algorithms (Exercise Set 6)

K-means is only one of a ton of clustering algorithms. Here is a few other clustering algorithms:

A. Affinity Propagation 

B. Spectral Clustering

C. Ward's Method 

D. Agglomerative Clustering

E. DBSCAN
