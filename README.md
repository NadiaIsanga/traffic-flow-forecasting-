# traffic-flow-forecasting-
# 🚦 Traffic Flow Forecasting Using Univariate & Multivariate Time Series Models

This project applies statistical and machine learning techniques to forecast urban traffic flow using time series data from highway sensors. It explores both temporal and spatial dependencies to improve prediction accuracy and support smarter urban mobility decisions.

---

## 📌 Summary

Forecasted short-term traffic patterns using univariate models (ARIMA, Exponential Smoothing) and multivariate techniques (Random Forest, Kalman Filter, VAR).  
Enhanced multivariate Random Forest model achieved the best performance (RMSE: 0.0111, MAPE: 9.76%).  
Integrated weather and network topology data to capture complex traffic dynamics.  
Findings inform traffic control strategies across key highway intersections in Northern Virginia/D.C.

---

## 🛠️ Skills Used

- **Time Series Forecasting**
- **Python / scikit-learn / statsmodels**
- **Random Forest & Kalman Filter**
- **Granger Causality Analysis**
- **VAR (Vector AutoRegression)**
- **Multivariate Feature Engineering**
- **RMSE / MAE / MAPE / MASE Evaluation**


---

## 🚀 How to Run

1. Clone the repository  
   `git clone https://github.com/NadiaIsanga/traffic-flow-forecasting.git`

2. Open the notebook  
   `cd traffic-flow-forecasting/code`  
   `jupyter notebook traffic_forecasting_notebook.ipynb`

---

## 🔎 Key Results

- Random Forest outperformed traditional models like ARIMA and Seasonal Naive.
- Kalman Filter adapted well to real-time traffic variability.
- Node 25 (central sensor) had the most accurate forecasts due to network positioning.
- Spatial relationships (via Granger causality) and weather variables enriched model reliability.

---


---


