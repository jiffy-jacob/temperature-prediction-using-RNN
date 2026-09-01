# Weather Temperature Prediction using SimpleRNN

## Project Overview

This project uses a **Simple Recurrent Neural Network (SimpleRNN)** to predict the **next day's temperature** based on historical weather data.

The model uses the previous **7 days of weather information** to forecast future temperature.

## Features Used

* Temperature (C)
* Humidity
* Wind Speed (km/h)

##  Project Workflow

1. Load and explore the weather dataset
2. Convert hourly weather data into daily data
3. Check and handle missing values
4. Visualize temperature trends
5. Normalize features using `MinMaxScaler`
6. Create 7-day sequences
7. Split data into training, validation, and test sets
8. Build and train a SimpleRNN model
9. Evaluate the model using:

   * MAE
   * RMSE
   * R² Score
10. Compare actual vs predicted temperatures
11. Forecast the next 7 days

##  Model Architecture

```text
Input Layer
     ↓
SimpleRNN (32 units)
     ↓
Dropout (0.2)
     ↓
Dense Layer (1 unit)
```

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

## Results

The model is evaluated using:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

The project also visualizes:

* Temperature trends over time
* Training vs Validation Loss
* Actual vs Predicted Temperatures
* Next 7 Days Temperature Forecast

##  Dataset

The project uses historical weather data containing temperature, humidity, wind speed, and other weather-related information.

##  Conclusion

This project demonstrates how a **SimpleRNN** can be used for time-series forecasting by learning patterns from previous weather observations to predict future temperatures.

