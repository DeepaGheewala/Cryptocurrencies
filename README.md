# Cryptocurrencies

## Overview
Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. So, they’ve asked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to follow below steps:-

* 1) [Preprocessing the Data for PCA](#D-1-Preprocessing-the-Data-for-PCA)
* 2) [Reducing Data Dimensions Using PCA](#D-2-Reducing-Data-Dimensions-Using-PCA)
* 3) [Clustering Cryptocurrencies Using K-means](#D-3-Clustering-Cryptocurrencies-Using-K-means)
* 4) [Visualizing Cryptocurrencies Results](#D-4-Visualizing-Cryptocurrencies-Results)

# D-1 Preprocessing the Data for PCA
 Steps taken for preprocessing -
 * Read the dataset CSV([crypto_data.csv](https://github.com/DeepaGheewala/Cryptocurrencies/files/8988775/crypto_data.csv))
 * Filter all Trading data
 * Filter out all not null Algorithms
 * Drop the IsTrading Column
 * Filter all data with TotalCoinsMined > 0
 * Put all CoinNames into an new Coin Dataframe
 * Drop the CoinName columns from the main Datatframe
 * using get_dummies() make all the character columns to interger
 * Scale the dataframe using StandardScaler()
 <p align="center"> <img src="https://user-images.githubusercontent.com/99355701/175863611-8e425c49-a81f-413a-9121-2eed550fbd4f.jpg"  align="center" height="200" width="500"> <img src="https://user-images.githubusercontent.com/99355701/175863433-7e0f00a3-8308-47b9-a111-ce8a16010b34.jpg"  align="center" height="200" width="500"> </p>
 



# D-2 Reducing Data Dimensions Using PCA
![PCData](https://user-images.githubusercontent.com/99355701/175863534-f7ca50be-56ce-4d25-9dde-56c28d43a479.jpg)

# D-3 Clustering Cryptocurrencies Using K-means

# D-4 Visualizing Cryptocurrencies Results
