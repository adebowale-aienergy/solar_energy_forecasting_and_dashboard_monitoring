Solar Energy Forecasting and Dashboard Monitoring Using Machine Learning
Welcome to this applied machine learning project focused on solar energy forecasting using real-world environmental data. This project explores and compares several powerful regression models for predicting daily solar radiation and is tailored for global applicability,especially beneficial for energy professionals, researchers, and clean energy enthusiasts.
Project Objective

The goal of this project is to develop a reliable machine learning pipeline that can accurately predict daily solar radiation (kWh/m²) based on multiple meteorological parameters (e.g., temperature, humidity, solar angles, wind speed, etc.). Accurate solar forecasting is crucial for:

- Designing and scaling solar PV systems

- Power demand management

- Energy policy planning

- Integrating renewables into smart grids
Global Scope

Though the initial environmental data was modeled around Lagos, Nigeria, the methodology, tools, and models can be easily adapted to any region worldwide using similar datasets such as those from NASA POWER or local weather stations

.Machine Learning Models Used

This project compares the performance of six machine learning regression models:

Model	MAE	RMSE	R² Score

Random Forest Regressor	0.12	0.14	0.9987
Polynomial Regression (D=2)	0.12	0.15	0.9985
XGBoost Regressor	0.12	0.17	0.9980
MLP Regressor (Neural Net)	0.27	0.33	0.9926
SVR (Support Vector Regressor)	0.36	0.72	0.9649
Linear Regression	0.23	0.28	0.0253
