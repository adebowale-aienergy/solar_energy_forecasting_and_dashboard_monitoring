Solar Energy Forecasting and Dashboard Monitoring Using Machine Learning

Welcome to this applied machine learning project focused on solar energy forecasting using real-world environmental data. 
This project explores and compares several powerful regression models for predicting daily solar radiation and is tailored for global applicability,especially beneficial for energy professionals, researchers, and clean energy enthusiasts.

Project Objective

The goal of this project is to develop a reliable machine learning pipeline that can accurately predict daily solar radiation (kWh/m²) based on multiple meteorological parameters (e.g., temperature, humidity, solar angles, wind speed, etc.). Accurate solar forecasting is crucial for:

- Designing and scaling solar PV systems

- Power demand management

- Energy policy planning

- Integrating renewables into smart grids
Global Scope

Though the initial environmental data was modeled around Lagos, Nigeria, the methodology, tools, and models can be easily adapted to any region worldwide using similar datasets such as those from NASA POWER or local weather stations

 Machine Learning Models Used

This project compares the performance of six machine learning regression models:

| Model                            | MAE   | RMSE  | R² Score |
|----------------------------------|-------|-------|----------|
| Random Forest Regressor          | 0.12  | 0.14  | 0.9987   |
| Polynomial Regression (Degree 2) | 0.12  | 0.15  | 0.9985   |
| XGBoost Regressor                | 0.12  | 0.17  | 0.9980   |
| MLP Regressor (Neural Net)       | 0.27  | 0.33  | 0.9926   |
| SVR (Support Vector Regressor)   | 0.36  | 0.72  | 0.9649   |
| Linear Regression                | 0.23  | 0.28  | 0.0253   |

Conclusion:
The ensemble models (Random Forest and XGBoost) performed exceptionally well, offering minimal error and near-perfect prediction accuracy — ideal for solar forecasting tasks.


 Tools & Technologies

- Google Colab (for modeling and visualizations)

- Python (Pandas, Numpy, Scikit-learn, XGBoost, Seaborn, Matplotlib)

- NASA POWER API (for solar radiation and weather parameters)

- GitHub (for version control and collaboration)

- Jupyter Notebooks (.ipynb format for each model)

  📁 Project Structure
  
  solar_energy_forecasting_and_dashboard_monitoring/
│
├── notebooks/
│   ├── solar_energy_forecasting_linear_regression.ipynb
│   ├── solar_energy_forecasting_polynomial_regression.ipynb
│   ├── solar_energy_forecasting_random_forest_regression.ipynb
│   ├── solar_energy_forecasting_XGBoost_regression.ipynb
│   ├── Standard Vector Regressor.ipynb
│   └── MLP_Regressor.ipynb
│
├── data/
│   └── solar_data_cleaned.csv  # NASA POWER sample dataset
│
├── README.md
└── LICENSE


Visualization & Dashboard (Coming Soon)

Interactive visual dashboards and charts will be added in future iterations for better insight and stakeholder presentations. These will include:

- Real-time solar intensity visualization

- Forecast trend plots

- Regional performance comparisons

 How to Run the Project

1. Clone the repo
   git clone https://github.com/adebowale-aienergy/solar_energy_forecasting_and_dashboard_monitoring

2. Open any of the .ipynb files using Google Colab or Jupyter Notebook.


3. Follow through each notebook to:

- Load the dataset

- Train models

- Evaluate and visualize results

Author

Adebowale Immanuel Adeyemi
Electrical Engineer | Solar Energy Specialist | Machine Learning Enthusiast
🔗 LinkedIn

License

This project is licensed under the MIT License , feel free to use and build upon it for educational or commercial use with attribution.





