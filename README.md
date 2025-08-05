# Optimizing-Driver-Allocation-Forecasting-Taxi-Demand-with-Machine-Learning

Project Goal Sweet Lift Taxi, a company providing airport taxi services, wants to improve driver availability during peak hours by predicting the number of taxi orders in the next hour. Our task is to develop a machine learning model that can accurately forecast hourly taxi demand based on historical data.

Objective Build and evaluate several machine learning models to predict hourly taxi orders. The model should achieve a Root Mean Squared Error (RMSE) of no more than 48 on the test set.

Dataset Description

Source: taxi.csv

Column: num_orders – the number of taxi orders per time interval

Datetime is provided in the index and must be resampled to hourly intervals

Project Workflow

Preparation: Load the data, perform resampling, and engineer relevant time-based and lag features.

Analysis: Visualize trends, seasonality, and perform sanity checks on data quality.

Training: Train and tune multiple models including Linear Regression, Random Forest, and LightGBM.

Testing: Evaluate model performance using RMSE and select the best model.
