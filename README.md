Predictive Maintenance of Solar Panels Using Digital Twins – Statistical vs Deep Learning Time Series Forecasting
📌 Overview

This project investigates predictive maintenance for solar photovoltaic (PV) systems by integrating Digital Twin technology with time-series forecasting models. The study compares traditional statistical methods (ARIMA, SARIMA) with advanced deep learning approaches (LSTM, PatchTST) to optimize reliability, minimize downtime, and enhance operational efficiency of solar plants
.

The work demonstrates how Digital Twins provide real-time simulation, monitoring, and forecasting capabilities to predict system failures early, reduce maintenance costs, and support sustainable energy goals
.

🎯 Objectives

Apply time-series forecasting for early fault detection in solar panels.

Compare the performance of statistical models (ARIMA, SARIMA) vs. deep learning models (LSTM, PatchTST).

Integrate forecasting into a Digital Twin framework for real-time decision-making.

Identify trade-offs between accuracy, computational cost, and robustness under varying weather conditions
.

🛠 Methodology

The project follows the CRISP-DM framework:

Business Understanding – Optimize solar PV efficiency and reliability.

Data Understanding – Solar output, weather, irradiance, and related features.

Data Preparation – Resampling, cleaning, and feature engineering.

Modeling – ARIMA, SARIMA, LSTM, and PatchTST models.

Evaluation – Metrics such as MAE, MSE, MAPE, and MASE.

Deployment – Digital Twin integration for real-time monitoring
.

📊 Results

ARIMA & SARIMA: Struggled with hourly data, producing oversimplified forecasts.

LSTM: Best performing model with low error rates, capturing short-term variability and long-term seasonal trends.

PatchTST: Efficient and scalable, but less robust under extreme weather conditions.

Key Insight: LSTM provided the best trade-off between accuracy and computational efficiency, while PatchTST showed promise for scaling
.

📈 Key Metrics

MAE, MSE, MAPE, MASE used for model comparison.

LSTM achieved lowest error rates across all datasets.

PatchTST yielded 73% MAPE under extreme conditions but remained computationally lightweight
.

🚀 Future Work

Extend forecasting framework to other renewable energy sources (hydro, geothermal, biomass).

Explore hybrid models combining statistical and deep learning approaches.

Enhance interpretability of deep learning models for practical deployment.

Implement real-world digital twin prototypes for solar farms
.

📚 Keywords

Predictive Maintenance · Solar PV · Digital Twin · ARIMA · SARIMA · LSTM · PatchTST · Time Series Forecasting · Renewable Energy

👨‍💻 Author

MSc. in Data Analytics Research Project - Parimal Sawant
