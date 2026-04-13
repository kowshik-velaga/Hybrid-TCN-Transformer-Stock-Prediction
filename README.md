# Hybrid TCN-Transformer for Stock Price Prediction

## Overview
This project implements a hybrid deep learning model combining Temporal Convolutional Networks (TCN) and Transformer with multi-head attention for stock price prediction.

The model captures:
- Short-term dependencies using TCN  
- Long-term dependencies using Transformer attention  

It is evaluated across multiple sectors including Banking, Automobile, Steel, and Pharma.

---

## Features
- Hybrid TCN + Transformer architecture  
- Uses technical indicators:
  - SMA (Simple Moving Average)
  - EMA (Exponential Moving Average)
  - RSI (Relative Strength Index)  
- Supports multiple stocks  
- Scalable and generalizable implementation  

---

## Stocks Used
The model is designed to work with multiple stocks, including:

- HDFCBANK.NS  
- DCB.NS  
- M&M.NS  
- ASHOKLEY.NS  
- JSWSTEEL.NS  
- JINDALSTEL.NS  
- SUNPHARMA.NS  
- AUROPHARMA.NS  

The implementation is generalized and can be applied to any stock by modifying the ticker input.

---

## Methodology
1. Data collection using Yahoo Finance  
2. Data preprocessing and normalization  
3. Feature engineering using technical indicators  
4. Sequence generation for time-series modeling  
5. Model training using Hybrid TCN-Transformer  
6. Evaluation using:
   - MAE
   - MSE
   - RMSE
   - R² Score  

---

## Important Note
Hyperparameters were tuned on representative stocks and applied across other datasets to ensure generalization of the model.

---

## How to Run
1. Install required libraries  
2. Open the notebook  
3. Change the ticker value to run for different stocks  
4. Run all cells  

---

## Future Work
- Integration of real-time news sentiment analysis  
- Use of external economic indicators  
- Advanced missing value imputation techniques  
- Multi-step forecasting  

