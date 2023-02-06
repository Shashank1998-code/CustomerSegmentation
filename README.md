# CustomerSegmentation
Retail Customer Segmentation using Unsupervised Non-Linear Clustering Technique


Customer segmentation is simply grouping customers with similar characteristics. 
These characteristics include geography, demography, behavioural, purchasing power, situational factors, personality, lifestyle, psychographic, etc. 
The goals of customer segmentation are customer acquisition, customer retention, increasing customer profitability, customer satisfaction, 
resource allocation by designing marketing measures or programs and improving target marketing measures.

Clustering is an efficient technique used for customer segmentation. Clustering places homogenous data points in a given dataset. 
Each of these groups is called a cluster [2]. While the objects in each cluster are similar between themselves,
they are dissimilar to the objects of other groups. Clustering is a type of data mining approach in machine learning classified under unsupervised learning 
This is because it is able to discover patterns and information from unlabelled data. It is used extensively in machine learning, classification, 
and pattern recognition.

Clustering algorithms include the K-means algorithm, hierarchical clustering. 
In this project, the k-means clustering algorithm has been applied in customer segmentation. 
K-means is a clustering algorithm based on the principle of partition. The letter k represents the number of clusters chosen. 
It is the most common centroid-based algorithm.


The steps of K-means clustering are:

1. Determine the number of clusters (k).
2. Select initial centroids.
3. Map each data point into the nearest cluster (most similar to centroid).
4. Update the mean value (centroid) of each cluster.
5. Repeat step 3–4 until all centroids are not changed.

The data includes the following features:

1. Customer ID
2. Customer Gender
3. Customer Age
4. Annual Income of the customer (in Thousand Dollars)
5. Spending score of the customer (based on customer behaviour and spending nature)

Conclusion

The result of the analysis shows that the retail store customers can be group into 5 clusters or segments for targeted marketing.

Cluster 1 (green): These are average income earners with average spending scores. They are cautious with their spending at the store.

Cluster 2 (yellow): The customers in this group are high income earners and with high spending scores. 
They bring in profit. Discounts and other offers targeted at this group will increase their spending score and maximize profit.

Cluster 3 (red): This group of customers have a higher income but they do not spend more at the store.
One of the assumption could be that they are not satisfied with the services rendered at the store. 
They are another ideal group to be targeted by the marketing team because they have the potential to bring in increased profit for the store.

Cluster 4 (purple): Low income earners with low spending score. 
I can assume that this is so because people with low income will tend to purchase less item at the store.

Cluster 5 (blue): These are low income earning customers with high spending scores. 
I can assume that why this group of customers spend more at the retail store despite earning less is because 
they enjoy and are satisfied with the services rendered at the retail store.


