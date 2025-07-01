

# 🪙 Bitcoin Price Prediction 

This project explores and compares different models to predict the price of Bitcoin using traditional financial indices, crypto variables, and mining-related metrics. Used historical data and applied multiple statistical and machine learning approaches including regression, random forest, and LSTM neural networks.

📊 Project Summary

Bitcoin has evolved from being considered a speculative asset to gaining institutional and even sovereign-level adoption. The goal of this project is to identify and analyze the key factors influencing Bitcoin's price and develop predictive models that can capture its complex dynamics.

🎯 Objectives

Predict Bitcoin price using various features including crypto asset prices, financial indices, mining difficulty, and popularity trends.

Compare the accuracy and limitations of different models: Linear Regression, Random Forest, and LSTM.

Understand the correlation and temporal relationships of Bitcoin with other variables like Ethereum, Litecoin, Gold, NASDAQ, and NYSE.

🧠 Models Implemented

✅ 1. Linear Regression

High R² (0.999), but not suitable due to non-normality and time series nature of data.

🌲 2. Random Forest Regressor

Handled non-linearity and lag-based feature engineering.

Showed improved RMSE over linear regression.

🔁 3. LSTM Neural Network

Best performance for time-series prediction.

Lowest RMSE: 100.21

Close match between predicted and actual values.

🗂️ Data Sources

Crypto Prices & Volumes: Yahoo Finance, Quandl (NASDAQ Data Link)

Gold, NASDAQ, NYSE: Yahoo Finance

Bitcoin Popularity: Google Trends

Time Frame: January 2015 to February 15, 2024 (daily data)

📈 Key Features Used

BTC (price in USD)

Gold (price in USD)

Litecoin, Ethereum prices

BTC Volume, Mining Difficulty, BTC Popularity

NYSE and NASDAQ indices

Bitcoin Cash price

📌 Insights & Observations

High correlation between BTC, Ethereum, Litecoin, NASDAQ, and NYSE — indicating institutional interest.

Mining difficulty positively correlates with BTC price due to increased scarcity.

Bitcoin halving events (2016, 2020) have significant long-term impact on price.

LSTM captured temporal dependencies better than other models.

🚧 Limitations

External macroeconomic shocks and policy changes (e.g., China mining ban) weren't directly modeled.

Missing data was interpolated; crypto vs. traditional market trading days mismatched.

Limited modeling of halving events and policy interventions.

📌 Conclusion

LSTM models proved most effective for forecasting Bitcoin prices in a time-series context. Future models can benefit from incorporating halving schedules, policy events, and real-time sentiment analysis.

📚 References
Bloomberg, Yahoo Finance, NASDAQ Data Link

BTC Halving History: Investopedia

Google Trends
