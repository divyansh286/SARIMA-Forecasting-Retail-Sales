# 📊 Retail Sales Forecasting using SARIMA

**Author:** Divyansh Dwivedi  
  
**Project Duration:** March–April 2025

---

## 🧠 Abstract

This project aims to analyze and forecast seasonal retail sales data using SARIMA (Seasonal AutoRegressive Integrated Moving Average) modeling. The goal is to model and predict the monthly sales of a specific product—**Fancy Beer**—leveraging classical time series techniques while also understanding seasonal trends, cyclic behaviors, and long-term movements in the data.

---

## 🎯 Motivation

Retail chains rely heavily on demand forecasting for inventory planning and logistics. The unpredictable nature of seasonal demand (like holiday spikes) requires robust models. SARIMA offers a structured and interpretable solution for such use cases, especially when dealing with univariate time series data.

---

## 📂 Project Structure
Retail-Sales-Forecasting-SARIMA
### Data 
#### Dataset used for training & testing 
### Note book
#### Jupyter notebook with code & outputs 
### plots
#### All the visualizations (trend, seasonality, residuals) 
### final_Report
#### Final PDF report with explanations & results 
### README.md 
#### You're reading it right now! 
### LICENSE 
#### MIT License


---

## 📁 Dataset Description

- **Data Source:** Retail sales records (Monthly)
- **Target Variable:** Monthly sales of “Fancy Beer”
- **Features:** Timestamped sales values
- **Format:** `.csv` with columns - `Date`, `Sales`

---

## 🧪 Exploratory Data Analysis

- Missing value checks
- Monthly trend analysis
- Outlier handling
- Time series decomposition
- Visualization of seasonal patterns

---

## 🔍 Time Series Modeling

We applied the following steps:

- ACF and PACF plots to identify orders
- Stationarity testing using ADF Test
- SARIMA parameter tuning (`p`, `d`, `q`, `P`, `D`, `Q`, `s`)
- Model diagnostics
- Rolling forecast and performance evaluation

---

## 📈 Results

- The SARIMA model captured both the trend and seasonality.
- RMSE and MAPE scores were used for evaluation.
- Actual vs Predicted graph showed accurate forecasting performance for the future periods.

---

## 📌 Key Takeaways

- Classical models like SARIMA are powerful for structured univariate time series.
- Forecasting seasonal retail products is more effective when seasonal components are separated and modeled.

---

## 🧠 Pipeline

```mermaid
graph TD
A[Raw Sales Data] --> B[Data Cleaning]
B --> C[EDA & Decomposition]
C --> D[SARIMA Modeling]
D --> E[Prediction]
E --> F[Result Analysis & Reporting]


