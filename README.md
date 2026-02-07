## Sales Forecasting Project
This repository contains a set of Jupyter Notebooks used for sales forecasting, data preprocessing, exploratory analysis, and model development. The project aims to predict future agricultural input sales based on historical data using time series forecasting methods, complemented by one machine learning approach.

### Notebooks Overview
1. SalesForecastingBTEDA.ipynb  
   This notebook focuses on the exploratory data analysis (EDA) of the sales data. It includes visualization of temporal patterns, seasonality, variability, outlier detection, autocorrelation analysis (ACF and PACF), and stationarity testing. The analysis provides the foundation for model selection and preprocessing decisions.

2. SalesForecastingBT_DataProcessing.ipynb  
   This notebook documents the data preprocessing steps applied to the sales data. It addresses bulk sales redistribution, handling of missing timestamps, outlier assessment, aggregation to weekly and monthly frequencies, and log transformation. These steps ensure temporal consistency and prepare the data for forecasting models.

3. ForecastingPreprocessedDataBT.ipynb  
   This notebook applies classical time series forecasting models, including the Naive method, Holt–Winters, SARIMA, and Prophet. It contains model estimation, parameter selection, and evaluation using appropriate forecasting error metrics and visualizations.

4. RandomForests.ipynb  
   This notebook implements a Random Forest regression model as a complementary machine learning approach. Temporal features such as lag variables and calendar indicators are constructed to enable forecasting. The notebook includes model training and performance evaluation.
