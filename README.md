In this project, we've analyzed the historical data of the Bitcoin-USD exchange rate, including open, close, high, and low prices. We've also examined the dataset's features, such as the difference between high and low prices (diffhl) and the difference between open and close prices (diffoc). Additionally, we've incorporated external data, such as the number of trades, to further enhance our analysis.

The main steps of the project can be summarized as follows:

Importing necessary libraries and mounting Google Drive to access the dataset.
Reading the main dataset (BTC-USD.csv) and performing an exploratory data analysis (EDA).
Visualizing price trends based on time series data.
Investigating the distributions of each numerical variable in the dataset using histograms and kernel density plots.
Merging the main dataset with an additional dataset (btc_data_bi_day.csv) containing the number of trades.
Visualizing the number of trades based on time series data.
Performing a statistical analysis and hypothesis testing on the number of trades.
For the statistical analysis and hypothesis testing, we calculated the mean and standard deviation of the number of trades. We then plotted a normal distribution with the calculated mean and standard deviation. Finally, we investigated whether there were significant statistical differences between high and low prices with respect to open and close prices of the same day.

The project provides valuable insights into the trends and characteristics of the Bitcoin-USD exchange rate and can serve as a foundation for more advanced analyses or predictive modeling.
