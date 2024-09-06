# weather-prediction

This project is completed by Nicola Rosca, as part of the MSc Data Science and Artificial Intelligence at Goldsmiths, University of London, 2023-24 cohort. 

This thesis is concerned with the long-term forecasting of the temperature in London (UK) and Lima (Peru). Using nine years worth of daily temperature data, the models used in this project are: 
- XGBoost
- Naive-Forecaster
- Auto-ARIMA
- SARIMAX
- LSTM

Each model is tuned with a grid search in order to obtain optimal resuls and is tested with MAE, MSE, RMSE, R2, and MAPE performance metrics. These metrics are compared with each other in order to showcase the best model. 

RESULT: The best model for this time series comparison study is the XGBoost, with a MAE of 2.1 for London and 0.67 for Lima. It was the model that could predict closest to the actual values out of all of them. The PDF added to this repository will explain in detail the context of this experiment, the methodology and the results. 
