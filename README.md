# ClusteringModel

Datast Link:
kaggle.com/datasets/vijayuv/onlineretail?select=OnlineRetail.csv

(Details about the dataset is present in report also)


Using K Means and Hierarchical Clustering and dividing data into 3 clusters after some pre processing and making 3 new columns:
- R (Recency):      Number of days since last purchase.
- F (Frequency):    Number of transactions.
- M (Monetary):     Total amount of transactions (revenue contributed).


Inference from the model:
- K-Means Clustering with 3 Cluster Ids 
  - Customers with Cluster Id 1 are the customers with high number of transactions as compared to other customers. 
  - Customers with Cluster Id 1 are frequent buyers. 
  - Customers with Cluster Id 2 are not recent buyers and hence least of importance from business point of view. 


- Hierarchical Clustering with 3 Cluster Labels 
  - Customers with Cluster_Labels 2 are the customers with high number of transactions as compared to other customers. 
  - Customers with Cluster_Labels 2 are frequent buyers. 
  - Customers with Cluster_Labels 0 are not recent buyers and hence least of importance from business point of view

(SCREENSHOTS FOR THE INFERENCE CAN BE SEEN IN REPORT)
