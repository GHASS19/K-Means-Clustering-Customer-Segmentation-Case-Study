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

- Choosing K: The Silhouette method. The average silhouette score suggests that we use 5 clusters

- Choosing K: The Gap statistic method

- Visualizing clusters with PCA: Exercise Sets 4 and 5

## 4. Conclusions and next steps

- Conclusions
- Other clustering algorithms (Exercise Set 6)

