![90457](https://github.com/user-attachments/assets/e504c22b-f596-47a3-8090-10499bd67a7a)
# Sales forecasting 
Goal: Utilize the provided historical dataset to forecast the upcoming 6 months.
This is a time series problem, we need to use lagged values which are previous values of the time series used as predictors for future values.
For example, to predict the value at time t, we can use the values at times t−1, t−2, etc., as features.

### Before starting the analysis, I consider the following aspects:

1. What's important info about data?
This dataset comprises monthly sales data, indicating the importance of time-series analysis. We have various predictive modeling options for sales forecasting, including linear regression, Random forest, and XGBoost. Additionally, considering the temporal nature of the data, employing Hidden Markov models could effectively capture und
patterns and trends.

2. What are features selected for sales estimation?
The main goal is to estimate sales figures for each product over time. This involves understanding sales fluctuations, identifying seasonal patterns, and uncovering
trends or irregularities.

3. Is there interdependence among product sales?
 Recognizing the potential interconnectedness or influence of product sales on each other is crucial. Factors like cross-selling, complementary products, or markets
affect the sales performance of individual products.
