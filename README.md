# CryptoClustering
 
In this challenge, we use our knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

See below for instructions.

Prepare the Data

Find the Best Value for k Using the Scaled DataFrame

Answer the following question in your notebook: What is the best value for k?

Cluster Cryptocurrencies with K-means Using the Scaled DataFrame

Retrieve the explained variance to determine how much information can be attributed to each principal component and then answer the following question in your notebook:

What is the total explained variance of the three principal components?

Create a new DataFrame with the scaled PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.


Find the Best Value for k Using the PCA DataFrame
Use the elbow method on the scaled PCA DataFrame to find the best value for k using the following steps:


Answer the following question in your notebook:
What is the best value for k when using the scaled PCA DataFrame?
Does it differ from the best k value found using the original scaled DataFrame?

Cluster Cryptocurrencies with K-means Using the PCA DataFrame

Initialize the K-means model with the best value for k.

Answer the following question:
What is the impact of using fewer features to cluster the data using K-Means?
