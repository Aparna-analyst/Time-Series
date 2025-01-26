

---

# **Time Series Forecasting with Python**

## **Overview**
This repository showcases a collection of time series forecasting projects implemented in Python. It covers a variety of models and techniques, including AR, ARIMA, SARIMA, VAR, Exponential Smoothing, Moving Average, Holt-Winters methods, and STL Decomposition. These projects demonstrate forecasting trends, seasonal patterns, and dependencies in time series data using real-world datasets.

---

## **Repository Structure**
This repository contains time series analysis using various models:

- [Time Series Smoothing](https://github.com/Aparna-analyst/Time-Series/tree/timeseries_smoothing/)
- [AR model (AutoRegressive)](https://github.com/Aparna-analyst/Time-Series/blob/AR-model/README.md?plain=1/)
- [ARIMA (AutoRegressive Integrated Moving Average)](https://github.com/Aparna-analyst/Time-Series/blob/ARIMA-model/README.md?plain=1/)
- [SARIMA (Seasonal ARIMA)](https://github.com/Aparna-analyst/Time-Series/blob/SARIMA-model/README.md?plain=1/)
- [VAR (Vector AutoRegression)](https://github.com/Aparna-analyst/Time-Series/blob/VAR-model/README.md?plain=1/)


---

## **How to Run the Project**
This project is developed in Google Colab. Follow these steps to run the notebooks:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/time-series-forecasting.git
   cd time-series-forecasting
   ```

2. Open Google Colab ([https://colab.research.google.com/](https://colab.research.google.com/)).

3. Upload a notebook file (e.g., `AR_model.ipynb`) by clicking on **File > Upload Notebook**.

4. Upload the corresponding dataset from the `datasets/` folder into the Colab environment.

5. Update the dataset file path in the notebook if necessary.

6. Run the notebook cells sequentially to reproduce the results.

---

## **Models Included**

### **1. AR Model (`1_Daily_minimum_temps.csv`)**
- **Description**: AutoRegressive (AR) models forecast time series data based on past observations. It captures the dependency between a current observation and its lagged values.
- **Dataset**: Daily minimum temperature dataset.
- **Objective**: Predict future minimum temperatures using an AR model.

---

### **2. ARIMA Model (`MaunaLoaDailyTemps.csv`)**
- **Description**: The ARIMA model combines autoregression (AR), differencing (I), and moving average (MA) to handle non-stationary data and trends.
- **Dataset**: Daily temperature readings from the Mauna Loa Observatory.
- **Objective**: Forecast future temperatures using ARIMA.

---

### **3. SARIMA Model (`airline-passenger-traffic(1).csv`)**
- **Description**: Seasonal ARIMA (SARIMA) extends ARIMA by including seasonal components, ideal for data with clear seasonality.
- **Dataset**: Monthly airline passenger traffic data.
- **Objective**: Forecast seasonal passenger traffic.

---

### **4. VAR Model (`PCEPersonalSpending.csv`, `M2SLMoneyStock.csv`)**
- **Description**: Vector AutoRegression (VAR) is a multivariate model that captures dependencies across multiple time series.
- **Dataset**: U.S. Personal Consumption Expenditure and Money Stock data.
- **Objective**: Analyze interdependencies and forecast future values of these economic indicators.

---

### **5. Exponential Smoothing (`Electric_Production.csv`)**
- **Description**: Exponential smoothing assigns exponentially decreasing weights to past observations, making it effective for forecasting data with trends or seasonality.
- **Dataset**: Monthly electricity production data.
- **Objective**: Smooth and forecast electricity production trends.

---

### **6. Moving Average Method (`Electric_Production.csv`)**
- **Description**: A simple method that uses the average of a fixed number of past observations to predict the next value.
- **Dataset**: Monthly electricity production data.
- **Objective**: Identify trends and forecast electricity production.

---

### **7. Holt-Winters and Holt’s Linear Methods (`Electric_Production.csv`)**
- **Description**: Holt-Winters extends Holt’s Linear Trend model by adding a seasonal component, making it suitable for seasonal data.
- **Dataset**: Monthly electricity production data.
- **Objective**: Model seasonality and trends for improved forecasting.

---

### **8. STL Decomposition (`Electric_Production.csv`)**
- **Description**: STL (Seasonal and Trend decomposition using Loess) separates a time series into seasonal, trend, and residual components.
- **Dataset**: Monthly electricity production data.
- **Objective**: Analyze and visualize the individual components of the time series.

---

## **Datasets**
1. **1_Daily_minimum_temps.csv**: Daily minimum temperature readings.
2. **MaunaLoaDailyTemps.csv**: Daily temperature readings from Mauna Loa.
3. **airline-passenger-traffic(1).csv**: Monthly airline passenger traffic data.
4. **PCEPersonalSpending.csv**: U.S. personal consumption expenditure data.
5. **M2SLMoneyStock.csv**: Money stock dataset.
6. **Electric_Production.csv**: Monthly electricity production data.

---

## **Results**
Each notebook includes:
- Data preprocessing (e.g., handling missing values, stationarity checks).
- Model implementation and parameter tuning.
- Forecasts vs. actual values visualized through plots.
- Performance evaluation using metrics like RMSE and MAE.

---

## **Future Enhancements**
- Add advanced models like LSTM and Facebook Prophet for forecasting.
- Develop an interactive dashboard for time series visualization and forecasting.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---





