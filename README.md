# Predicting-market-movements
Building AI course project

## Summary

Automatic trading strategy using a RNN model with additional explanatory variables to predict future market movements. The output of the RNN model makes the basis for automatic long and short positions in forex / cryptocurrency trades.


## Background

The model aims to effectively compete against human traders and beat the market return using data-driven predictions on up or down movements of candlesticks.
Creating a robust algortihm which trades automatically and wins on a constant basis is difficult considering the random walk nature of the financial markets.


## How is it used?

The Python script including the RNN model predictions are linked to the TradingView platform. Based on the probable movements, the algorithm specifies SL and TP points and executes the trade. The algorithm can be used by anyone interested in creating cumulative passive profits and eventually reach finanical freedom. However, it is to be noted that an algorithm with a precision of 100 % is nearly impossible, and thus, this model aims to only predict correct movements at least 70 % of the time. The most difficult aspect in this project is to determine the right explanatory variables for the input of the neural network model.


## Data sources and AI methods

Training and testing data for the model is found from whichever platform containing financial time series data. Yahoo Finance is used for this model.
One of the variables include interpreting financial news topics. Data is scraped from websites like for instance, FinViz.

## Challenges

The model will not be able to take the right position continously and thus, it requires patience and significant backtesting to make it perform better than the average raw guess.
