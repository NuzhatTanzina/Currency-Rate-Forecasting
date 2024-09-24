# Currency-Rate-Forecasting
Foreign currency exchange rate prediction using ARIMA and Random Forest models
his repository contains the source code and methodology used in our research on predicting foreign exchange rates using a hybrid model combining Autoregressive Integrated Moving Average (ARIMA) and Random Forest Regression (RFR). This project aims to enhance accuracy in forecasting exchange rates by leveraging the strengths of both models.
Table of Contents

    Introduction
    Methodology
        ARIMA Model
        Random Forest Model
        Hybrid Model
    Installation
    Usage
    Dataset
    Evaluation Metrics
    Results
    Future Work
    Contributors
    License

Introduction

Foreign exchange rates play a critical role in global financial markets. Accurate predictions of these rates are essential for risk management and decision-making. This project introduces a hybrid model that integrates ARIMA for handling linear temporal dependencies and Random Forest for capturing non-linear relationships.
Methodology
ARIMA Model

ARIMA is a popular time-series forecasting model that captures historical data patterns and applies autoregression to forecast future values.
Random Forest Model

Random Forest is a machine learning algorithm that builds an ensemble of decision trees to predict based on multiple subsets of the dataset, improving overall model robustness and accuracy.
Hybrid Model

The hybrid model combines the strengths of both ARIMA and Random Forest by first applying ARIMA to the dataset and then using Random Forest to refine the predictions on non-linear data points.
Dataset

The dataset used in this research contains historical foreign exchange rates for major currency pairs (EUR/USD, GBP/USD, CHF/USD, AUD/USD) between December 2003 and August 2022. It is available here.
Evaluation Metrics

The following metrics were used to evaluate the performance of our models:

    Mean Absolute Error (MAE)
    Mean Squared Error (MSE)
    Root Mean Squared Error (RMSE)
    Mean Absolute Percentage Error (MAPE)

Results

The hybrid model showed improved performance over individual ARIMA or Random Forest models, particularly in handling both linear and non-linear data.

    RMSE: 0.00584
    MSE: 0.00003
    MAE: 0.00466

Future Work

We aim to expand this project by:

    Applying the model to a broader range of currencies.
    Enhancing the model's interpretability.
    Improving its performance across different market conditions.
