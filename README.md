# F10: Tempetature and humidity predicion for North America three locations
# Group 6
- Mihhail Batura
  
**Background**
- Some businesses in southern Canada experience financial losses due to inaccurate winter weather forecasts. Current forecast accuracy is approximately 75% for humidity and 80% for temperature. These errors directly affect energy costs during the heating season, because in coastal areas temperatures can vary from –5°C to 10°C. Warehouses must maintain stable temperature and humidity levels to protect stored goods, making better forecasts essential. The goal is to develop a more accurate model that can reduce winter losses by approximately 10–15%.

**Goals**
- Select and compare suitable machine learning methods for weather forecasting
- Train the models to capture regional weather patterns in North America
- Evaluate performance on actual observations and achieve RMSE < 1.5°C for temperature and RMSE < 5% for humidity

**Data**
- Historical hourly weather data for Montreal, Toronto, and Dallas (2013–2016) from Kaggle was used for model training. Hourly weather data from Open-Meteo for 2023 served as the test dataset. Dallas was included as a contrasting location due to its more continental and variable southern climate relative to southern Canada.
- List:
- initial train data  - https://www.kaggle.com/datasets/selfishgene/historical-hourly-weather-data/data
- inital test data - https://open-meteo.com/

**Methodology** 
- Two machine learning models were used for weather forecasting in this study: a Random Forest regressor and a Multilayer Perceptron (MLP) neural network. Both models were trained using historical hourly meteorological data from Montreal, Toronto, and Dallas. The feature set included atmospheric variables (temperature, humidity, pressure, wind speed, wind direction) as well as engineered time-related features such as hour, month, cyclical month encoding (sin/cos), and temperature lag values (1-hour, 24-hour, and 24-hour rolling mean).
- Model performance was evaluated on 2023 test data using two standard metrics: Mean Absolute Error (MAE) and Root Mean Square Error (RMSE). The Random Forest served as a strong baseline, while the MLP provided a neural-network approach for comparison.

**Steps and working hours**
- ...

**P.S. Edited Jupyper Notebooks coming soon!**


