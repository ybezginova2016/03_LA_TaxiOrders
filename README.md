# 03_LA_TaxiOrders
Machine learning model for forecasting the number of taxi orders in the next hour.

## Project Description

The client company ABC, providing taxi driving services, wants to understand when (at what time during the day) the number of orders increases to be prepared and attract more taxi drivers for such 'hot' hours in order to satisfy demand. Hence, the company ABC wants to receive a valid machine learning model for predicting demand for an upcoming hour.

## Project Methodology

1. Use archived data provided by the client.
2. Resample the data by an hour.
3. Split the data into train, valid and test samples.
4. Train different ML models with different hyperparamters.
5. Choosing the model ML model, making conclusions.
6. Quality Metric RMSE: Root Mean Square Error <= 40

## Project Outcomes
- The best model is *Linear Regression* wit RMSE = 45.45.
- Target value for RMSE < 48 as agreed with the client.
- Time Series is a hard type of data to train. Hence, even though the best RMSE score is for *lightGBM* algorithm, it is worth considering less complex forecasting models such as *Linear Regression*.

## Key Python Libraries
- numpy, pandas, lightgbm, seaborn
- sklearn.ensemble
- sklearn.tree
- sklearn.linear_model
- sklearn.metrics
- sklearn.preprocessing

### Code: https://github.com/ybezginova2016/03_LA_TaxiOrders/blob/main/03_LA_taxi_orders_main.ipynb
