# CryptoClustering
Use my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

BEFORE BEGINNING:
Create Repo
Clone Repo
Push Changes to GitHub
Download Files

Instructions
Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.
Load the crypto_market_data.csv into a DataFrame.

1)Prepare the Data
Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

2)Find the Best Value for k Using the Scaled DataFrame
Use the elbow method to find the best value for k 

3)Cluster Cryptocurrencies with K-means Using the Scaled DataFrame

4)Retrieve the explained variance to determine how much information can be attributed to each principal component 

5)Create a new DataFrame with the scaled PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

6)Find the Best Value for k Using the PCA DataFrame
Use the elbow method on the scaled PCA DataFrame to find the best value for k 

7)Cluster Cryptocurrencies with K-means Using the PCA DataFrame

8)Color the graph points with the labels found using K-means.

