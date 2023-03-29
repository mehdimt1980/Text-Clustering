This project applies clustering techniques to the text of Hobbes's Leviathan to explore patterns and themes in the book. Specifically, we use K-means clustering to group similar sections of the book together based on their TF-IDF vector representation, and then visualize the clusters using bar charts.

Data

The text of Leviathan was obtained from Project Gutenberg (https://www.gutenberg.org/ebooks/3207). The raw text was preprocessed by removing stop words and applying n-gram range of (1,2) to extract relevant features.

Dependencies

Python 3

numpy

scikit-learn

matplotlib


Results

We determined the optimal number of clusters using the elbow method, and found that 5 clusters provided a good balance between interpretability and cluster quality. We then identified the top words for each cluster and visualized them using bar charts. The results provide insights into the main themes and ideas discussed in Leviathan, as well as the organization of the book.

Future Work
Explore different clustering algorithms and distance metrics to compare the results with the current analysis
Perform topic modeling on the text to identify latent themes and compare with the results of clustering
Apply sentiment analysis to explore the emotional tone of different sections of the book
