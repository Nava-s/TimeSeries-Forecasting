# Time Series Forecasting Project

## Overview

Welcome to the Time Series Forecasting Project! This project is an educational endeavor focused on predicting store sales for a large Ecuadorian-based grocery retailer, Corporación Favorita. The objective is to use time-series forecasting techniques to predict unit sales across various items sold at different stores.

## Project Description

The project involves building a predictive model to forecast sales using historical data. The data includes information on store locations, item details, promotions, and sales figures. Through this project, you will practice and enhance your machine learning skills by working with time-series data.

### Data

The dataset used in this project is derived from a Kaggle competition designed for learning purposes. It contains:
- **Date:** The specific date of the sales data.
- **Store:** Information about the store where the sales occurred.
- **Item:** Details about the items sold.
- **Promotions:** Data on any promotions that were active.
- **Sales:** The actual unit sales figures.

### Model Details

The following key changes were made between the initial and updated versions of the model:

1. **Data Merging and Preprocessing:**
   - **Version 1:** Combined data from various sources (stores, transactions, oil prices, holidays) and included extensive outlier removal and feature engineering.
   - **Version 2:** Focused on a more streamlined approach, incorporating only the holiday dataset and removing outliers. 

2. **Feature Engineering:**
   - **Version 1:** Included detailed processing of holiday data, no outlier removal, and additional features related to time and vacations.
   - **Version 2:** Simplified feature set by retaining only the most relevant features based on correlation and removed outliers.

3. **Model Changes:**
   - **Version 1:** Used Lasso Regression.
   - **Version 2:** Transitioned to a Keras Sequential Model for improved performance.

4. **Lag Variables:**
   - **Version 1:** Included multiple lag features.
   - **Version 2:** Retained only those lags with the highest correlation.

### Evaluation

The performance of the model is evaluated using the Root Mean Squared Logarithmic Error (RMSLE). The RMSLE measures the difference between the predicted and actual sales values, providing insight into the model's accuracy. 

### Performance Improvement

The model has significantly improved from an initial RMSLE of 3.3 to a current RMSLE of 1.46, demonstrating better accuracy in forecasting sales.

## Get Started

To understand how to start with time series forecasting, we recommend reviewing the Time Series course available on Kaggle. This course guides you through making your first submission and is based on winning solutions from past competitions.

## Context

Accurate forecasting is crucial for grocery stores to balance inventory levels, minimize waste, and enhance customer satisfaction. This project simulates real-world forecasting challenges, providing valuable insights and experience in handling time-series data.

