# Cryptocurrencies

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

For this challenge, since there is no known output for what Martha is looking for, we used unsupervised learning to cluster the data, processing the data to reduce the dimensions of the table, and reducing the principal components using PCA.

## Results

We found that the Cryptocurrencies can be classified into 4 groups,

![newplot](https://user-images.githubusercontent.com/90414330/157748629-673a1ea0-6c08-4d6e-a064-94582088f691.png)

When making a Scatter Plot between: *TotalCoinSupply* and *TotalCoindMined* we find that the 3rd cluster consists in an outlier. While the 1st cluster has a few coins mined but it can also take high values in the supply of the coins.

![bokeh_plot](https://user-images.githubusercontent.com/90414330/157748626-3955fe6e-e5d1-48f9-a2fb-e753fc995ef9.png)

