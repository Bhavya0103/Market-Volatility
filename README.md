# Market Volatility Analysis

## Overview
This project, **Market Volatility Analysis**, leverages time-series modeling techniques to analyze stock market fluctuations and improve financial risk forecasting. The analysis is performed on stock market data using various statistical and machine learning models, including **GARCH, ARIMA, and LSTM**.

## Features
- **Data Preprocessing**: Handles missing values and prepares data for modeling.
- **Exploratory Data Analysis (EDA)**: Visualizes stock price trends and volatility.
- **GARCH Model**: Estimates market volatility.
- **ARIMA Model**: Performs time-series forecasting.
- **LSTM Model**: Implements a deep learning-based prediction model.
- **Risk Assessment**: Calculates Value at Risk (VaR) and Monte Carlo simulations.

## Dataset
The following datasets are used:
- **calendar.csv**: Provides date-related metadata.
- **sales_train_evaluation.csv**: Contains historical sales data.
- **sales_train_validation.csv**: Holds sales validation data.
- **sample_submission.csv**: Sample format for predictions.
- **sell_prices.csv**: Includes product pricing history.

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn statsmodels arch scikit-learn tensorflow
```

## Usage
1. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook Market Volatility.ipynb
   ```
2. **Run each cell sequentially** to:
   - Load and preprocess data
   - Perform EDA
   - Apply statistical and machine learning models
   - Visualize results

## Results
- **GARCH Model**: Estimates time-varying volatility.
- **ARIMA Model**: Provides time-series forecasting.
- **LSTM Model**: Predicts future market trends using deep learning.
- **Visualizations**: Graphs for stock trends, volatility, and model predictions.

## Author
**Bhavya Sharma**

## License
This project is open-source and available under the MIT License.

