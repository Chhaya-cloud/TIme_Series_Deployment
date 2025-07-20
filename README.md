This project performs in-depth **time series analysis** and **forecasting** on monthly gold prices using **ARIMA** and **SARIMA** models. It also features a full-fledged **Streamlit app** for interactive exploration, model selection, and dynamic forecasting.
Project Features
**Visualization** of trends over time
- **STL decomposition** to separate trend, seasonality, and noise
- **ADF test** for stationarity
- **Differencing** to make the series stationary
- **ACF and PACF plots** to determine model orders
- **Model building** with ARIMA and SARIMA

- Interactive Streamlit Web App:
- Choose between ARIMA and SARIMA models
- Forecast up to 36 months into the future
- Visualize forecast with **confidence intervals**

-  ACF & PACF Interpretation Tips:

* ACF with spikes at seasonal lags → Add seasonal terms
* PACF cut-off after lag p → Suggests AR model order
* ACF cut-off after lag q → Suggests MA model order

Technologies
* Python
* Pandas, Matplotlib, Statsmodels
* yfinance for data fetching
* Streamlit for UI
* Pickle for model persistence
