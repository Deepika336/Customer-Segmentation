# DLithe Internship Certification Program
Reference:Assignment during Online Internship with Dlithe(www.dlithe.com)
Project done under the guidance of: DLite
Done by:M.Deepika     USN:4nm18cs084
Batch 2

## Customer Segmentation using k-means clustering
A technique to divide the customers based on their purchase history, gender, age, interest, etc. It is useful to get this information so that the store can get help in personalize marketing and provide customers with relevant deals.

First step involved in this poject is exploring and visualizing the data set.

## Data Visualizing using Histogram:
When exploring a dataset, you’ll often want to get a quick understanding of the distribution of certain numerical variables within it.
 A common way of visualizing the distribution of a single numerical variable is by using a histogram. 
A histogram divides the values within a numerical variable into “bins”, and counts the number of observations that fall into each bin.
 By visualizing these binned counts in a columnar fashion, we can obtain a very immediate and intuitive sense of the distribution of values within a variable.
 
## k-means clustering
K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.A cluster refers to a collection of data points aggregated together because of certain similarities. You'll define a target number k, which refers to the number of centroids you need in the dataset.

### Steps for applying k-means:
1. **Choose optimal number of clusters using**
**Elbow Method:**
The elbow method is used to determine the optimal number of clusters in k-means clustering. The elbow method plots the value of the cost function produced by different values of k.
 As you know, if k increases, average distortion will decrease, each cluster will have fewer constituent instances, and the instances will be closer to their respective centroids.
 However, the improvements in average distortion will decline as k increases.
 The value of k at which improvement in distortion declines the most is called the elbow, at which we should stop dividing the data into further clusters.
2. **Select k random points from the data as centroids**
3. **Assign all the points to the closest cluster centroid**
4. **Recompute the centroids of newly formed clusters**
5. **Repeat steps 3 and 4 until:**
* Centroids of newly formed clusters do not change
* Points remain in the same cluster
* Maximum number of iterations are reached.











