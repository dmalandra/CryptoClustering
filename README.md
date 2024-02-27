# Crypto Clustering

This challenge utilizes Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.  After scaling the data found in the Resources folder, I used a k-means model to fit and predict crypto trends.  There were several overlapping clusters of data, so I decided to reduce the number of features by incorporating a PCA model.  By limiting the number of features to three, I was able to see more robust separation of the clustered data when running the predictive model.
