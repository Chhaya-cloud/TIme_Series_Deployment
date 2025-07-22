Gold Price Forecasting App (Time Series Project with Streamlit)

This project predicts future gold prices using Time Series Analysis techniques like ARIMA and SARIMA. It also includes a user-friendly Streamlit web app where you can interactively choose the model and forecast upcoming months.

Project Features

#Data & Analysis
- Uses historical monthly gold prices (from `gold_prices.csv`)
- Trend and seasonality analysis
- Stationarity check using ADF Test
- Data transformation with differencing
- ACF & PACF plots to decide model parameters
- Time Series modeling using ARIMA and SARIMA
- Forecasting for up to 36 months
- Compare model performance using AIC/BIC

#Streamlit App Highlights
- Easy-to-use interface to select model (ARIMA or SARIMA)
- Forecasting options for next 1 to 36 months
- Visualization of predictions and confidence intervals
- View model details and download results

## Folder Structure
├── app.py # Main Streamlit app
├── gold_prices.csv # Dataset with historical gold prices
├── arima_model.pkl # Trained ARIMA model (auto-generated)
├── sarima_model.pkl # Trained SARIMA model (auto-generated)
├── requirements.txt # List of required Python packages
└── README.md # Project summary and instructions

Install Required Libraries:pip install -r requirements.txt
Launch the Streamlit App: streamlit run app.py

Technologies
* Python
* Pandas, Matplotlib, Statsmodels
* yfinance for data fetching
* Streamlit for UI
* Pickle for model persistence
