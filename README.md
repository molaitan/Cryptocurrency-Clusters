# Cryptocurrency Clusters

## Background for Assignment

* You are on the Advisory Services Team of a financial consultancy. One of your clients, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They’ve asked you to create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.

* You have been handed raw data, so you will first need to process it to fit the machine learning models. Since there is no known classification system, you will need to use unsupervised learning. You will use several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. You will use data visualization to share your findings with the investment bank.

### Steps Taken

1. Prepared Data by cleaning and standardizing the values
2. Perform dimensionality reduction with PCA
3. Reduce the dataset dimensions with t-SNE and use output to create scatter plot (image below)
4. Use Cluster Analysis with k-Means to create an elbow plot (image below)

![image](https://user-images.githubusercontent.com/94502554/167766509-f7967527-2af8-4a2d-ad32-5827e43c92fb.png)

![image](https://user-images.githubusercontent.com/94502554/167766445-ef88ca63-4d6e-42a0-8d4a-d42808432f80.png)

### Recommendation

The elbow plot of the scaled data does not have a clear elbow. Thus, it's unclear what the best value of "k" to choose. This indicates there is no meaningful clustering within this data set.

There is one single cluster showing for the t-NSE output but no identifiable clustering with the elbow plot. It may be possible to try another method of determining the optimal k. However, so far, my recommendation for the investment bank is to reevaluate whether grouping cyrptocurrencies together is the right thing to do because there are no true clusters that developed from the algorithms we explored.
