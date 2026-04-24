# Weekly-CL1-Oil-Price-Forecasting
I am a graduate student in Financial Economics focusing on time-series forecasting and asset pricing.
This repository showcases my work in how I construct model Weekly forecasting of WTI crude oil front-month (CL1) prices using time-series models. Includes data processing, model implementation, and out-of-sample evaluation with MSFE and statistical tests.

# Weekly Crude Oil Price Forecasting Project

I developed a real-time forecasting system for weekly WTI crude oil prices using time-series modeling techniques in R. The model is based on an AR(1) growth framework, where weekly price dynamics are captured through estimated percentage changes and applied to end-of-week prices to generate forward-looking forecasts.

Over a sample of 67 weekly forecasts, the model achieved:

Mean Absolute Error (MAE): ~1.88 USD per barrel
Directional Accuracy (Success Ratio): ~53.7%

The results highlight a key insight consistent with financial economics literature: oil prices exhibit near-random walk behavior, making accurate prediction inherently challenging. While the model provides reasonable magnitude forecasts, directional prediction remains only marginally better than chance.

This project demonstrates:

Strong ability in time-series modeling and forecasting evaluation
Practical experience with out-of-sample testing and performance metrics (MAE, directional accuracy)
Understanding of market efficiency and benchmark comparison (random walk behavior)
End-to-end workflow: data processing → model estimation → forecasting → evaluation

The forecasting system is continuously updated with new data, forming a live performance track record, and is intended to serve as a transparent, reproducible portfolio of applied econometric modeling in energy markets.
