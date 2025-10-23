# 🛒 Walmart Sales Forecasting — Time Series Analysis with ARIMA, SARIMAX, FBProphet & LSTM

# 📘 Overview

This project focuses on time series forecasting of Walmart’s weekly sales using a combination of statistical and deep learning models. The goal is to analyze historical sales data, capture seasonality and trends, and build predictive models that can help in demand planning, inventory management, and business decision-making.

# 🚀 Objectives

Perform exploratory data analysis (EDA) to understand patterns, trends, and seasonality in sales data.

Preprocess and transform time series data for model readiness.

Build and compare multiple forecasting models — ARIMA, SARIMAX, Facebook Prophet, and LSTM.

Evaluate models using metrics like RMSE, MAE, MAPE, and R².

Visualize forecasts and residual errors for interpretability.

# 🧠 Models Implemented

ARIMA (AutoRegressive Integrated Moving Average):
Captures linear dependencies and short-term autocorrelation in the sales data.

SARIMAX (Seasonal ARIMA with Exogenous Variables):
Extends ARIMA by incorporating seasonality and external regressors like holidays, fuel prices, and temperature.

Facebook Prophet:
Handles seasonality, holidays, and trend changes intuitively with automatic hyperparameter tuning.

LSTM (Long Short-Term Memory):
A deep learning approach that learns complex temporal dependencies and non-linear patterns for long-term forecasting.

# ⚙️ Workflow

Data Preparation: Parse dates, handle missing values, resample weekly, and scale features.

Feature Engineering: Add holiday flags, moving averages, and lag features.

Model Training: Fit each forecasting model with hyperparameter optimization.

Evaluation: Compare models on validation set and visualize results.

Forecast Visualization: Plot actual vs. predicted sales and next-week forecasts for performance insights.

# 📈 Results

Each model provides unique insights:

ARIMA/SARIMAX: Strong for short-term, seasonal predictions.

FBProphet: Great interpretability and holiday effect handling.

LSTM: Captures non-linear and long-term patterns effectively.

# 🧩 Tech Stack / Dependencies

Python 3.x

pandas, numpy, matplotlib

scikit-learn

statsmodels (for ARIMA, SARIMAX)

fbprophet or prophet

tensorflow or keras (for LSTM)

# 🏁 Conclusion

This end-to-end project demonstrates how hybrid time series forecasting approaches can improve retail demand prediction. By comparing traditional and neural network-based models, we gain insights into the strengths of each method for different forecasting horizons and data complexities.

## 📬 Connect With Me

This repository is a valuable resource for data scientists and analysts interested in practical time series forecasting with retail sales data.

Feel free to raise issues or contribute improvements to enhance forecasting accuracy and efficiency!

**👩‍💻 Shanila Anjum**

📧 [shanilaanjum07@gmail.com](mailto:shanilaanjum07@gmail.com)
🌐 [GitHub Profile](https://github.com/Shaneela07)
🔗 <a href="https://www.linkedin.com/in/shaneela-anjum/"><img src="https://img.shields.io/badge/linkedin-%230A66C2.svg?style=plastic&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
