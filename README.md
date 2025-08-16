# ML Stock Forecasting  

## Overview  
**ML Stock Forecasting** is a machine learning project that applies predictive modeling techniques to financial time series data. The goal is to forecast stock price trends by combining data preprocessing, feature engineering, and model evaluation.  

This project was originally developed under the name *ValueInvestor* and has now been refactored and documented for clarity, reproducibility, and professional presentation.  

---

## Goals  
- Predict stock price valuations on a **daily, weekly, and monthly** basis.  
- Provide **BUY / HOLD / SELL** recommendations.  
- Maximize capital returns through data-driven decision-making.  

---

## Features  
- **Exploratory Data Analysis (EDA):** Stock trends, volatility, and correlations.  
- **Data Preprocessing:** Cleaning, normalization, and feature generation from financial datasets.  
- **Predictive Modeling:** Machine learning methods applied to stock price forecasting.  
- **Model Evaluation:** Performance comparison using metrics such as RMSE, MAPE, and directional accuracy.  
- **Reproducibility:** Clear Jupyter notebooks for experimentation and results replication.  

---

## Methodology  
1. **Data Ingestion** – Stock datasets loaded from multi-sheet Excel files.  
2. **Feature Engineering** – Includes moving averages, volatility, Bollinger Bands, and local maxima for trading signals.  
3. **Modeling** –  
   - Implemented **LSTM (Long Short-Term Memory)** neural networks for time series forecasting.  
   - Applied dropout layers to prevent overfitting.  
   - Tuned hyperparameters using **GridSearchCV + KerasRegressor**.  
4. **Evaluation** –  
   - Measured accuracy with RMSE and MAPE.  
   - Tested BUY / SELL / HOLD recommendation logic.  
5. **Scenarios Tested** –  
   - *Single Sheet Model*: Prototype and trading strategy validation.  
   - *All Sheets Model*: Applied forecasting pipeline across multiple stock datasets.  

---

## Results  
- LSTM models produced stable forecasts across daily, weekly, and monthly horizons.  
- Integration of technical indicators (e.g., Bollinger Bands) provided interpretable BUY/HOLD/SELL signals.  
- Demonstrated potential to maximize capital returns through data-driven forecasting. 

