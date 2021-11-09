## Cryptocurrencies Clustering

Purpose:
To apply unsupervised learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

Phases:
Preprocessing the Data for PCA
1. Loading data as pandas dataframe
2. filtering tradeable coins
3. filtering coins with algorithms
4. drop record with missing values
5. drop records with zero values
6. transform categorial features
7. scale data using sklearn StandardScaler method

Reducing Data Dimensions Using PCA
1. reducing dimensions with Principal Component Analysis techniques to 3 components

Clustering Cryptocurrencies Using K-means
1. create the elbow curve to compute number of clusters (k value)
2. fit k-mean clustering model 
3. predict clusters for each data point
4. assign cluster labels to data points

Visualizing Cryptocurrencies Results
1. creating 3d cluster plot based on 3 principal components
2. creatin scatter plot based on standardized total number of coin supply and coin mining 