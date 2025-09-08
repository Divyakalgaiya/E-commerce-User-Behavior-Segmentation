**Project title: E-commerce User Behavior Segmentation**
**Type: Customer Segmentation**
**Technique used: Hierarchical Clustering**

**Project Objectives**
Segment e-commerce customers into meaningful groups using unsupervised clustering algorithms.
Visualize and interpret the resulting clusters for actionable business decisions.

**Dataset**
This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

Dataset Characteristics: Multivariate, Sequential, Time-Series

Subject Area: Business

Associated Tasks: Clustering

Feature Type: Integer, Real

Instances: 541909

Features: 6

**Hierarchical Clustering**
Hierarchical clustering is used to group similar data points together based on their similarity creating a hierarchy or tree-like structure. The key idea is to begin with each data point as its own separate cluster and then progressively merge or split them based on their similarity.

A dendrogram is like a family tree for clusters. It shows how individual data points or groups of data merge together.

Agglomerative (Bottom-Up): It starts with each data point as a single cluster and then merges the closest clusters iteratively until all data points are in a single cluster.
Divisive (Top-Down): This approach starts with all data points in a single cluster and then recursively splits the cluster into smaller clusters until each data point is in its own cluster.

**Observation**
High-Value Customers: Clusters characterized by low Recency (recent purchases), high Frequency (frequent purchases), and high Monetary values (high spending). These are likely the most valuable customers who should be targeted with retention strategies and special offers.
Losing Customers: Clusters with high Recency (haven't purchased recently) might represent customers who are drifting away. Re-engagement strategies could be crucial for this segment.
New Customers/Low-Value Customers: Clusters with low Frequency and Sales values could be new customers or those who make infrequent, low-value purchases. Strategies to encourage repeat purchases and increase spending could be relevant here.

**Conclusion**
By understanding these customer segments, the business can tailor marketing strategies, product offerings, and customer service approaches to better meet the needs and behaviors of their customers.
