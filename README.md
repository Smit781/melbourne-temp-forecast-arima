# Forecasting Melbourne Minimum Temperatures using ARIMA
## 📌 Objective

This project forecasts minimum daily temperatures in Melbourne using the ARIMA (AutoRegressive Integrated Moving Average) model. We predict the first 15 days of January 1991 and compare it with actual recorded temperatures.

---

## 📁 Files Included

- `Daily Minimum Temperatures in Melbourne.ipynb` – Complete time series forecasting notebook
- `daily-minimum-temperature csv data set.csv` – Input dataset from Kaggle (1981–1990)

---

## 🔍 Methodology

1. **Data Preprocessing**
   - Date parsing, null removal, basic EDA

2. **Visualization**
   - Time Series plot
   - Histogram
   - Monthly and Yearly trends
   - Rolling Mean analysis

3. **Stationarity Test**
   - Augmented Dickey-Fuller (ADF) test

4. **Model Selection**
   - Manual ARIMA Grid Search (best AIC)

5. **Forecasting**
   - 15-day prediction using the best model
   - Confidence Intervals

6. **Evaluation**
   - Comparison with actual values (sourced externally)
   - Error metrics: Difference, Absolute Error

---

## 📚 Data Sources

- Melbourne Temperature Data (1981–1990):  
  📌 [Kaggle - Daily Minimum Temperatures in Melbourne](https://www.kaggle.com/datasets/paulbrabban/daily-minimum-temperatures-in-melbourne)

- Actual Temperatures for Jan 1991 (for comparison):  
  📌 [Extreme Weather Watch - Melbourne 1991](https://www.extremeweatherwatch.com/cities/melbourne/year-1991)

---

## 🧠 Skills Demonstrated

- Time Series Forecasting  
- Statistical Testing  
- ARIMA Modeling  
- Data Visualization  
- Real-world evaluation using external data

---

## ✅ Run It Yourself

Make sure you have these Python libraries:
```bash
pip install pandas numpy matplotlib statsmodels
