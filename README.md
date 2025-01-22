# Stock Price Prediction


## Project Overview

This project aims to predict stock prices using a linear regression model. The focus is on cleaning and preprocessing the data, analyzing feature correlations, and evaluating model performance using cross-validation techniques. This project demonstrates foundational data science and machine learning techniques applied to real-world financial data.Linear, Ridge regression and LSTM models used for learning.

## Data Description

The dataset used in this project includes the following columns:

### Date: The date of the stock price.
### Open: Opening price of the stock.
### Close: Closing price of the stock.
### High: Highest price during the trading session.
### Low: Lowest price during the trading session.
### Volume: Number of shares traded.
Source
The data was sourced from Yahoo Finance for historical stock price information.

## Preprocessing Steps
Handling missing values.
Normalizing numerical features.
Creating new features such as daily price range (High - Low).
Splitting the data into training and testing sets.
Dependencies

## The project is implemented using the following libraries:

### pandas: Data manipulation and preprocessing.
### numpy: Mathematical operations.
### matplotlib and seaborn: Data visualization.
### scikit-learn: Machine learning (Linear Regression, train-test split, and cross-validation).
