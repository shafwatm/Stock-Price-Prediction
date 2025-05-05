# 📈 Stock Price Prediction Using XGBoost

A time series regression project that forecasts Apple (AAPL) stock closing prices using historical data and XGBoost.

## 🔍 Project Summary

- Collected 9 years of AAPL stock data using `yfinance`
- Engineered sliding-window features (100-day windows)
- Trained an XGBoost regressor to predict the next day's closing price
- Achieved strong performance: MAE ≈ $2.30, RMSE ≈ $3.75
- Visualized actual vs. predicted trends using `matplotlib`

## ⚙️ Tools & Libraries

- Python, yfinance, scikit-learn, XGBoost, matplotlib

## 🛠 Future Improvements

- Incorporate more features (OHLCV)
- Test LSTM or ARIMA for comparison
- Deploy as a web app with Flask or Streamlit

