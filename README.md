# Trading_App

This is a Stock Market Analysis and Prediction Web Application built with Streamlit. It provides investors and traders with comprehensive tools to analyze stocks, predict future prices, and calculate important financial metrics like Beta and CAPM returns.

# Key Features:


1. Stock Information Dashboard - View company fundamentals and historical data

2. Technical Analysis - Charts with RSI, MACD, Moving Averages

3. Stock Price Prediction - 30 day forecast using ARIMA model

4. CAPM Analysis - Calculate Beta and Expected Returns

5. Portfolio Analysis - Compare multiple stocks

   

# Tools and Libraries Used

1. Streamlit : Web application framework for creating the UI

2. Pandas : Data manipulation and analysis

3. NumPy : Numerical computing and mathematical operations

4. YFinance : Download stock data from Yahoo Finance

5. Pandas-Datareader : Fetch S&P500 data from FRED


# Trading_App/
│
├── Trading_App.py                 # Main landing page
├── pages/                         # Multi-page app structure
│   ├── Stock_Analysis.py         # Stock information & technical analysis
│   ├── Stock_Prediction.py       # ARIMA price prediction
│   ├── CAPM_Return.py            # Multi-stock CAPM analysis
│   └── CAPM_Beta.py              # Single stock beta calculation
│
├── utils/                         # Shared utility modules
│   ├── __init__.py               # Package initializer
│   ├── plotly_figure.py          # Chart generation functions
│   ├── capm_functions.py         # CAPM calculations
│   └── model_train.py            # ARIMA forecasting model
│
├── assets/                        # Static assets
│   └── app.jpeg                  # Application logo/image
│
└── requirements.txt               # Python dependencies








