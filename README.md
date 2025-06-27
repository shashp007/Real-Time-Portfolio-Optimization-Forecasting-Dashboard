Real-Time Portfolio Optimization & Forecasting Dashboard
Description
This project is a comprehensive financial dashboard built with Python and Dash. It fetches real-time stock data, performs time-series forecasting using both ARIMA and Prophet models, and calculates optimal portfolio allocation based on modern portfolio theory. The interactive interface visualizes key metrics like rolling volatility, Value at Risk (VaR), and optimal asset weights, providing a powerful tool for quantitative analysis and risk management.

Key Features
Real-Time Data: Integrates with the Financial Modeling Prep API and yfinance to fetch up-to-date stock data.

Predictive Forecasting: Implements and compares both ARIMA and Prophet models to forecast future price movements.

Mean-Variance Optimization: Uses the cvxpy library to calculate the optimal portfolio weights that minimize risk for a given set of assets.

Advanced Risk Metrics: Automatically calculates and displays rolling volatility and Value at Risk (VaR).

Interactive Dashboard: Built with Dash and Plotly for a dynamic and user-friendly experience.

