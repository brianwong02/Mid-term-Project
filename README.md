# Mid-Term Project
On top of clusters based on total confirmed COVID-19 cases and total confirmed COVID-19 deaths per neighborhood, we have also looked at the msot common type of health care that are in those neighborhoods. We used the Foursquare API to explore the most common healthcare venues in New York City. For this analysis, the data was clustered based on total most common venue in each neighborhood. We have used KMeans clustering and Hierarchical clustering to accomplish this analysis. 

# Results
With KMeans clustering, we were able to find the ideal number of clusters to be 2 using the Elbow Plot. We have also evaluated the cluster using the Silhouette score which gave back a score of 0.6168. With Hierarchical clustering, from the dendrogram used, we were able to see that the ideal number of clusters is 3 which gave a silhouette score of 0.4606. 

# Conclusion
We can see that KMeans clustering is a better model for segmentation of NYC neighborhoods compared to hierarchical clustering. The clusters between Kmeans and hierarchical clustering are similar with both cluster 0 having a most common healthcare category type to be Health and Medicine and the other being Doctors office. We verified the results with the silhouette score and can see the models are properly segmenting the neighbourhoods

