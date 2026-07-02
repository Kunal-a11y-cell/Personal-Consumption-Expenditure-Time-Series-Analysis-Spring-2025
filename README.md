Project Overview: 
Forecasting U.S. Personal Consumption Expenditures (PCE) using a SARIMAX (Seasonal ARIMA with exogenous variables) model built on macroeconomic indicators.

This project explores whether incorporating external economic signals improves time series forecasting performance compared to baseline models.

Objective: 
Forecast monthly PCE values using historical macroeconomic data
Evaluate impact of exogenous variables on prediction accuracy
Compare SARIMAX against baseline time series approaches
Analyze model limitations in macroeconomic forecasting

Data Sources:
Public U.S. macroeconomic datasets:
Federal Reserve Economic Data (FRED)
Bureau of Economic Analysis (BEA)
Bureau of Labor Statistics (BLS)

Key Variables:
Personal Consumption Expenditures (PCE) — target variable
Consumer Price Index (CPI)
Disposable Personal Income
Federal Funds Rate
Unemployment Rate
Retail Sales indicators

Approach: 
Data preprocessing: time alignment, missing value handling, stationarity checks
Feature engineering: lagged variables, log transforms, exploratory correlation analysis
Modeling: SARIMAX with seasonal components + exogenous macro variables
Baselines: naive and simple time series benchmarks
Evaluation: MAE, RMSE, visual forecast comparison

Key Results: 
SARIMAX captures overall trend and seasonality well
Exogenous variables showed limited and inconsistent improvement in short-term forecasts
Baseline models remained competitive in certain periods
Results suggest macro indicators have delayed or weak predictive power at monthly resolution

Limitations: 
Economic indicators are lagged and revised over time
Linear model structure may miss nonlinear macro relationships
Limited optimization of lag selection for exogenous variables
No real-time high-frequency financial signals included

Key Takeaways:
Feature complexity does not guarantee improved forecasting performance
Baseline models remain strong benchmarks in macroeconomic time series
Lag structure and data timing are critical in economic forecasting
Model interpretability is as important as predictive accuracy

Skills Demonstrated: 
Time series forecasting (SARIMAX / ARIMA)
Macroeconomic data analysis
Feature engineering for temporal datasets
Model evaluation (MAE / RMSE)
Python (pandas, statsmodels, numpy, matplotlib)
