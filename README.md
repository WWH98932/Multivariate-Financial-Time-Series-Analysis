Multivariate-Financial-Time-Series-Analysis

UCLA Master of Applied Economics Capstone Research

Data acquisition

I use Google stock prices range from January 2016 to June 2018 as the dependent variable. Then I used Topic Modeling (NMF and LDA) to find the topics from articles about Google and use them as independent features; used Textblob to get the sentiment index of Google from US major newspapers (See Topic Modeling and Sentiment Time Series). Then extract Google Trends Indices of these features and the stock prices / ETF prices data as well.

Data Pre-processing

Including data resampling (convert weekly data into daily), data scaling (normalize the data to get rid of the unit inifluence and prepare for machine learning usage) and stationary (basic assumption in time series analysis).

Feature Selection

Ridge, LASSO and ElasticNet Regression

Apply Different Models

Including ARIMAX, k-NN Regression, Regression Tree, Random Forest and LSTM networks.

Prediction Accuracy Comparison

