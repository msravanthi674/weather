# Weather Prediction Using RNN

## Project Overview
This project demonstrates the use of a Recurrent Neural Network (RNN) with LSTM layers to predict daily mean temperatures based on historical weather data. The dataset contains lagged weather variables, including temperature, humidity, pressure, and precipitation, to assist in accurate forecasting.

### **Load and Explore Dataset**
- The dataset (`JaipurFinalCleanData.csv`) contains weather data for Jaipur, India.
- Features include current and lagged values of temperature, humidity, pressure, and precipitation.
- Converted the `date` column to datetime format for better handling.
- Displayed dataset statistics and structure.

### **Model Evaluation**
- Made predictions on the test dataset.
- Evaluated the model's performance using:
  - Mean Squared Error (MSE): 0.9375
  - Mean Absolute Error (MAE): 0.7117
  - R² Score: 0.9740 (indicating strong predictive accuracy).


## Key Learnings
- Lagged variables are crucial for time-series forecasting.
- LSTM networks handle sequential dependencies effectively.
- Proper feature scaling and data reshaping are essential for RNNs. 
