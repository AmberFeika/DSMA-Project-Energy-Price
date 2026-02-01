# DSMA-Project-Energy-Price
Time series analysis for energy price


## Project Overview
This project focuses on forecasting price movements and volatility in energy markets using historical daily data for Brent crude oil, WTI crude oil, and natural gas.
The primary objective is to build, evaluate, and compare multiple prediction models—ranging from classical time-series approaches to machine learning methods—to understand their effectiveness in predicting short-term price dynamics and market risk.



## Initial Design 
The project will be developed iteratively using an Agile approach, starting with an initial design sprint (Sprint 0) to define the prediction scope, modeling strategy, and evaluation framework.

Planned stages include:
1. Data understanding and preprocessing  
    Load and clean daily energy price data  
    Convert prices to returns and define prediction horizons  
    Split data using time-aware training and testing schemes  

2. Feature engineering and exploratory analysis  
    Create lagged returns, rolling volatility, and trend features  
    Visualize feature behavior over time  
    Explore cross-commodity predictive signals  

3. Modeling and validation  
    Establish baseline models (random walk, ARIMA)  
    Train machine learning models (e.g., Lasso, Random Forest)  
    Tune hyperparameters using rolling or expanding windows  


4. Evaluation, comparison, and reporting  
    Evaluate forecasts using error and classification metrics  
    Compare performance across models and commodities  
    Interpret results in an energy market context  
