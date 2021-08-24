# Cryptocurrency Price Prediction
This repository contains an analysis with aim of predicting the closing price of cryptocurrencies.

Understanding the Context
After the boom and bust of cryptocurrencies’ prices in recent years, cryptocurrencies have been increasingly regarded as an investment asset. Because of their highly volatile nature, there is a need for good predictions on which to base investment decisions. Different existing studies have leveraged machine learning for more accurate cryptocurrency price prediction. We are interested in applying different modeling techniques to samples with different data structures (qualitative and quantitative data) and dimensional features to achieve an optimization in price prediction.

**NB:** The target value is the actual price. We have data extracted in an interval of 1h for a period of one year (from 1st of March 2020 to 1st of March 2021). We are interested in predicting the values of cryptocurrency prices in specific timestamps that we have in the validation file.

The data source can be found below:
Cryptocurrency Dataset: https://docs.google.com/document/d/1ElEYvVw0d-AwctprS5f7YhWrFm8GEkME5KSmUsqDcJY/edit

## *CONCLUSIONS*

From the analysis we carried out, the following are the observations we made:
* The volume traded didn't have a significant impact on the closing price of the crypto
* The market capitalisation, like expected, moved together with the price of a cryptocurrency
* The average opening price was 15288.15 while average closing price was 15290.42
* The most occuring opening price was 8962.01 while the most occuring closing price was  8947.23
* The maximum opening price was 61408.92 while the maximum closing price was 61259.67
* The minimum opening price was 4545.08 while minimum closing price was 4267.29


## *RECOMMENDATIONS*

* Investors should not solely rely on models to predict the prices of crypto prices because it is not guaranteed that whatever happened in the market in the past will have a bearing on what happens today as there are so many factors that should be taken into consideration.
* Exclusion of key indicators such as social media and volatility as key coefficients yet we know that they do have a bearing on the closing prices of crypto. We encourage investors to look at every other feature before deciding to speculate on crypto prices.
* There needs to be a timestamp for forecasting to properly be carried out. This basically means that for someone to forecast the prices of crypto they need to have a timestamp that shows seasonality and trends in the market.
