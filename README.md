# Gold Price Prediction | LSTM | 97% Accuracy

![pic](./gold_pic.webp)

## Project Overview

This project aims to build a time series model to predict future gold prices using historical data. Accurate gold price forecasting can be valuable for traders, investors, and financial analysts. We utilize 10 years of historical gold price data (from 2013 to 2023) to forecast prices for the next 30 days.

Two models are used in this project:
- **LSTM (Long Short-Term Memory) Model**
- **Dense Neural Network Model**

## Data
    

- **Dataset**: 10 years of daily gold price data (2013-2023).  [Link to dataset](./Gold_Price_2013-2023.csv)

- **Forecasting**: Predict gold prices for the next 30 days.

## Models

1. **LSTM Model**: 
   - Designed to handle time series data by capturing long-term dependencies.
   - This model is well-suited for sequential data, making it effective for gold price forecasting.

2. **Dense Neural Network Model**: 
   - A fully connected feedforward neural network.
   - Used as a comparison to the LSTM model to evaluate different approaches to forecasting.

## Results

### LSTM Model:
- **Test Loss**: 0.05435
- **Test MAPE (Mean Absolute Percentage Error)**: 2.25%
- **Test Accuracy**: 97.74% 🎯📈

### Dense Model:
- **Test Loss**: 0.04849
- **Test MAPE**: 6.54%
- **Test Accuracy**: 93.46% 🎯📈

## Conclusion

Both models performed well in predicting gold prices. The Dense Neural Network slightly outperformed the LSTM model in terms of accuracy and error metrics. These results indicate that the models are effective in predicting short-term price trends, providing useful insights for gold traders.



