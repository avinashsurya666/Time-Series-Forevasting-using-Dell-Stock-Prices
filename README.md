# Time-Series-Forevasting-using-Dell-Stock-Prices

# Time Series Forecasting: Dell Stock Prices

This project implements time series forecasting using Long Short-Term Memory (LSTM) neural networks to predict **Dell Technologies Inc. (DELL)** stock prices based on historical data. The stock data is retrieved using the Yahoo Finance API (`yfinance`), and the model is built using TensorFlow's Keras module.

## Project Overview

- **Data Source**: Yahoo Finance API via `yfinance`
- **Forecasting Method**: Long Short-Term Memory (LSTM) Neural Network
- **Goal**: Predict future Dell stock prices based on historical data
- **Libraries**: Python, `yfinance`, `numpy`, `pandas`, `matplotlib`, `sklearn`, `tensorflow`

## Table of Contents

1. [Dependencies](#dependencies)
2. [Data Retrieval](#data-retrieval)
3. [Project Structure](#project-structure)
4. [How to Run the Code](#how-to-run-the-code)
5. [Model Overview](#model-overview)
6. [Results](#results)
7. [Future Improvements](#future-improvements)

## Dependencies

Before running the project, ensure you have the following libraries installed:

```bash
pip install yfinance pandas numpy matplotlib scikit-learn tensorflow
