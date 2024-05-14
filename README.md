Projects Goal:
Gain practical experience by working with various clustering algorithms like hierarchical clustering and K-means.

Hierarchical Clustering

Study of the Project.

This section dives into the realm of unsupervised learning, where the goal is to uncover hidden structures and patterns within unlabeled data. Unlike supervised learning where we have predefined categories, unsupervised learning lets the data speak for itself, allowing us to discover natural groupings.
A technique for this task is hierarchical clustering. Here, data points are progressively grouped into a hierarchy of clusters based on their similarities. 

Visualizing Relationships: 
By traversing the hierarchy, we can observe how data points are related at different granularities. Tightly knit clusters at the bottom represent highly similar points, while higher levels reveal broader groupings with looser similarities.

Flexibility in Cluster Choice: 
The hierarchical structure provides flexibility in choosing the desired number of clusters. We can cut the tree at a specific level to obtain a fixed number of clusters, or analyze the entire hierarchy to understand the data's inherent groupings.

Linkage criteria. 
These criteria determine how the "closeness" between two clusters is calculated, essentially guiding how clusters are merged during the hierarchical process. Here's a glimpse into some common linkage criteria:

Ward's Method: A Focus on Compactness
The primary focus is on Ward's method, which stands out for its emphasis on minimizing within-cluster variance. When merging clusters, Ward's method prioritizes the pairing that results in the least increase in the overall variance within the newly formed cluster. This strategy often leads to more compact and spherical clusters, reflecting tighter data point cohesion.
![image](https://github.com/kameshraj333/unsupervised_learning-pca-and-cluster-/assets/162411498/d64c6db9-cda9-4cd3-a5c7-6656204d23cc)


K-Means Clustering: 

Finding Centroid-Based Groups
K-means clustering is another popular unsupervised learning technique. It works by:

Defining the number of clusters (k): 
This is a user-specified parameter that dictates the number of groups to be formed.
Initializing cluster centers (centroids): These initial centroids represent the "centers" of each cluster.
Iterative Refinement: Data points are assigned to the nearest centroid, and then the centroids are re-calculated based on the assigned points. 
This process iterates until convergence (minimal centroid movement).
K-means excels at finding spherical clusters.
![image](https://github.com/kameshraj333/unsupervised_learning-pca-and-cluster-/assets/162411498/b2231f5f-8626-4b6f-9f09-10e413833be7)

Gained and Outcome of the project.

Uncover Hidden Structures: 
Natural groupings and patterns lurking within unlabeled data.
Clustering reveals hidden relationship that traditional analysis might.

Art of grouping:
Able to classify data points into meaningful clusters based on their inherent similarities.
Clustering helps to categorize data points into well-defined groups, making it easier to understand and analyze.
Able to leverage clustering to uncover hidden patterns, segment data into meaningful groups, and gain a deeper understanding of the underlying structure within the information

