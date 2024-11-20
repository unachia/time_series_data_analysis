# Sales forecasting

Goal: Utilize the provided historical dataset to forecast the upcoming 6 months.
This is a time series problem. We need to use lagged values, which are previous values of the time series, as predictors for future values.
For example, to predict the value at time t, we can use the values at times t−1, t−2, etc., as features.

<img src="https://github.com/user-attachments/assets/0ed99b97-5620-48be-8b44-310193ba4041" width=50% height=50%>

### Before starting the analysis, I consider the following aspects:

1. What's important info about data?
This dataset comprises monthly sales data, indicating the importance of time-series analysis. We have various predictive modeling options for sales forecasting, including linear regression, Random forest, and XGBoost. Additionally, considering the temporal nature of the data, employing LSTM could effectively capture underlying patterns and trends. Using the traditional time series model is an efficient way to analyze 

3. What are features selected for sales estimation?
The main goal is to estimate sales figures for each product over time. This involves understanding sales fluctuations, identifying stationarity, seasonal patterns, and uncovering
trends or irregularities.

4. Is there interdependence among product sales?
 Recognizing the potential interconnectedness or influence of product sales on each other is crucial. Factors like cross-selling, complementary products, or markets
affect the sales performance of individual products.

#### Data Exploration: autocorrelation, transformation
#### Model Building: Construct the LSTM model using Keras.
#### Training: Train the model using your sales data.
#### Prediction: Use the trained model to predict and forecast future sales.
