# Cryptocurrencies

This project was an analysis of existing cryptocurrencies to provide insights into which were viable options for potential investors. The needs include filtering out non-active cryptos and understanding how the different options could be grouped.

### Preparation

Data from Cryptocompare was obtained and preprocessed including:

Removal of:

- Cryptocurrencies not trading
- Cryptocurrencies that do not have a defined algorithm
- Cryptocurrencies with incomplete data
- Cryptocurrencies without any coins mined
- Removal of columns not essential to the project
- Transformation of text values to dummy variables
- Standardization of data

### Method

The PCA algorithm was used to reduce the dimensions from the preprocessed data to three principal components.

The K-means algorithm was used to cluster the data by first creating an elbow curve to find the best value for K, then running the algorithm for that k value.

### Result

Challenge Jupyter Notebook contains a final table with viable options of cryptcurrencies currently tradable, as well as visualizations demonstrating how these cryptos could be best grouped.