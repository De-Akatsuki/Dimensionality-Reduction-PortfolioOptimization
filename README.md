# Deep Learning for Portfolio Optimization with Dimensionality Reduction

## Overview

This project aims to implement and extend a deep learning-based approach for portfolio optimization. Drawing inspiration from the paper "Deep Learning for Portfolio Optimization" by Zhang et al., this project integrates dimensionality reduction techniques to enhance the performance and robustness of deep learning models in dynamic financial markets. The framework circumvents the need for forecasting expected returns by directly optimizing portfolio weights, focusing on Exchange-Traded Funds (ETFs) across various asset classes.

## Project Goals

1.  **Implement a Deep Learning Model for Portfolio Optimization**:
    *   Develop a neural network model (e.g., LSTM, CNN, or FCN) that takes historical market data as input and outputs optimized portfolio weights.
    *   Optimize the model to directly maximize the Sharpe ratio of the portfolio.

2.  **Integrate Dimensionality Reduction Techniques**:
    *   Incorporate Principal Component Analysis (PCA), t-Distributed Stochastic Neighbor Embedding (t-SNE), and Autoencoders to reduce the dimensionality of input features.
    *   Evaluate the impact of these techniques on model performance, generalization, and computational efficiency.

3.  **Backtest and Evaluate Performance**:
    *   Backtest the model on historical data to assess its risk-adjusted returns and stability.
    *   Compare the performance of the deep learning model with traditional portfolio optimization strategies.

## Key Features

*   **Direct Sharpe Ratio Optimization**: Directly optimize portfolio weights, bypassing return forecasting.
*   **Dimensionality Reduction**: Enhance model performance and reduce overfitting using PCA, t-SNE, and Autoencoders.
*   **Diverse Asset Classes**: Trade Exchange-Traded Funds (ETFs) across stocks, bonds, commodities, and volatility indices.
*   **Dynamic Portfolio Weights**: Adapt portfolio allocations based on market conditions.
*   **Backtesting Framework**: Evaluate performance on historical data using key metrics like Sharpe ratio, Sortino ratio, and maximum drawdown.

## Technologies Used

*   **Programming Language**: Python
*   **Data Manipulation**: Pandas, NumPy
*   **Machine Learning**: TensorFlow, Keras, Scikit-learn
*   **Data Visualization**: Matplotlib, Seaborn
*   **Data Sources**:
    *   Yahoo Finance (yfinance)
    *   Alpha Vantage API
    *   CoinMarketCap

## Project Structure

