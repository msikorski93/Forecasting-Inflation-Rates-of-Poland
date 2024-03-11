# Forecasting-Inflation-Rates-of-Poland
Recently inflation is a popular topic in Poland and is highest since the 90s. Experts presume inflation in Poland should continue to rise. The time series forecasting was completed by implementing the autoregressive methods.

* New update for March 2024. Inflation values were forecasted with deep learning: CNN & LSTM. The out-of sample predictions confirm that Polish inflation will continue to fall. Based on evaluation metrics and model residuals, the CNN is a better choice.

|          | RMSE   | R<sup>2 | MAE    | MAPE [%] |
|----------|--------|---------|--------|----------|
| **CNN**  | 0.4008 | 0.9892  | 0.3012 | 0.1753   |
| **LSTM** | 0.4957 | 0.9835  | 0.3736 | 0.2218   |

* New update for March 2023.

![march_2023](https://user-images.githubusercontent.com/45270023/225881806-0ef77db7-9e9a-426d-88c2-0291da383201.jpg)

* The November 2022 is an updated and much fresher version of the forecast. It contains a SARIMA implementation.

![forecast](https://user-images.githubusercontent.com/45270023/202861900-a2e3db91-a6bf-4524-940f-1c95748eacde.jpg)

* The earlier notebook (December 2021) describes the ARIMA method (without seasonality order). The notebook contains factual errors both in code and description.
