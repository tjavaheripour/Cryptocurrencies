# Cryptocurrencies

## Overview of the project:

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked us to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
The data (crypto_data.csv) is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, we decided to use unsupervised learning. To group the cryptocurrencies, We decided on a clustering algorithm. We’ll use data visualizations to share our findings with the board.


## Results :
### - Clustering Crytocurrencies Using K-Means:
By using the knowledge of the K-means algorithm, we created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame

![ElbowCurve.PNG](https://github.com/tjavaheripour/Cryptocurrencies/blob/main/Images/ElbowCurve.PNG)

### - Visualizing Cryptocurrencies Results:
The clusters are plotted using a 3D scatter plot, and each data point shows the CoinName and Algorithm on hover

![ScatterClusters.PNG](https://github.com/tjavaheripour/Cryptocurrencies/blob/main/Images/ScatterClusters.PNG)

A hvplot scatter plot is created where the X-axis is "TotalCoinsMined", the Y-axis is "TotalCoinSupply", the data is ordered by "Class", and it shows the CoinName when you hover over the data point

![hvplotScatter.PNG](https://github.com/tjavaheripour/Cryptocurrencies/blob/main/Images/hvplotScatter.PNG)
