# 🌫️ Relative Humidity Forecasting using Time Series (AQI Project)

This project uses **Facebook Prophet**, a powerful time series forecasting tool, to predict **Relative Humidity (RH)** as part of air quality analysis, based on historical data.

## 📌 Project Overview

Air quality and environmental conditions like **humidity** play a vital role in public health and climate awareness. In this project, I’ve built a model that forecasts **RH (Relative Humidity)** over time, using real-world air quality data and Python libraries like **Pandas**, **Numpy**, **Prophet**.

> 📊 **Goal:** Forecast relative humidity levels to help understand atmospheric patterns and their relation to air quality.

## 🧠 What I Did

- Cleaned and preprocessed air quality data from the UCI dataset.
- Handled missing values(Using Mean of each col), incorrect decimal separators, and unnecessary columns.
- Explored the data using `.info()`, `.describe()`, and visual inspection.
- Used **Prophet** to model:
  - Overall trend in **RH**
  - Hourly seasonality
  - Future predictions (next 30 hours)
- Visualized the forecast using Prophet’s plotting functions.

## 🔧 Tools & Libraries Used

- Python
- Google Colab
- Pandas
- Facebook Prophet

## 📁 Dataset

- **Source:** UCI Air Quality Dataset  
- **Format:** CSV file with hourly measurements of various air pollutants and environmental metrics

## 📈 Forecasting

The model was trained to predict **Relative Humidity (RH)** using previous hourly data, generating a 365-hour forecast window. The forecast also includes confidence intervals to show prediction uncertainty.

> **Bonus:** I explored seasonal and hourly patterns in RH using Prophet’s built-in visualization tools.
