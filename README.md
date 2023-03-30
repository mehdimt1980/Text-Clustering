This project applies clustering analysis to the text of Hobbes's Leviathan, which is available on Project Gutenberg. The goal is to identify patterns in the text and group similar sections together.

Data

The data used in this project is the full text of Hobbes's Leviathan, which was downloaded from Project Gutenberg in plain text format.

Methods

The text data was preprocessed by removing stop words and stemming the remaining words. A TF-IDF vectorizer was then applied to convert the text data into a matrix of features.

The optimal number of clusters was determined using the elbow method, and k-means clustering was applied to group the text data into clusters. The top words for each cluster were identified using the centroid of the cluster and the TF-IDF values.

A dendrogram was also generated to visualize the hierarchical distances between clusters.
