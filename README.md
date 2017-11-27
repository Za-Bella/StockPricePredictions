# Stock Price Predictions using Machine Learning

In this project, I've implemented a Recurrent Neural Network with an [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) architecture to predict future stock prices, by training the model on more than 10 years of historical prices. 

The historical prices from January 2005 to May 2017 of these following stocks are located in the `datasets/` folder of this repository:
- AAPL (Apple)
- AMZN (Amazon)
- BRK-A (Berkshire Hathaway)
- GOOG (Google)
- IBM 
- SPY (S&P 500 tracker)

## Environment

Here is my [environment file](https://github.com/vinny-palumbo/StockPricePredictions/blob/master/environment.yaml). To clone my environment execute: `conda env create -f environment.yaml`