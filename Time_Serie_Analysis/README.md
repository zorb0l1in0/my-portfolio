# 📈 Time Series Analysis of Log Returns

This project focuses on the analysis of financial time series using **logarithmic returns (log returns)**. Log returns are commonly used in finance to normalize price changes and simplify calculations involving compounded returns.

## 🔍 Objective

To explore the statistical and temporal properties of a financial asset through log return transformation, and to analyze:
- Stationarity
- Volatility
- Trends and seasonality
- Correlation structure
- Autoregressive behavior

## 🛠️ Tools & Technologies

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Statsmodels  
- Scikit-learn (for regression and ML, if used)

## 📂 Contents

- `Analisis_de_serie_temporal_(LogReturn).ipynb`: main notebook containing all steps of the analysis, from data loading to visualization and statistical testing.

## 📊 Analysis Steps

1. **Data Preprocessing**:  
   - Load financial time series (e.g., stock prices)
   - Clean and format the data

2. **Log Return Calculation**:  
   \[
   \text{Log Return}_t = \log\left(\frac{P_t}{P_{t-1}}\right)
   \]

3. **Exploratory Data Analysis**:
   - Time series plotting
   - Distribution of log returns
   - Rolling statistics

4. **Stationarity Testing**:
   - Augmented Dickey-Fuller (ADF)
   - KPSS test

5. **Autocorrelation & Partial Autocorrelation**:
   - ACF/PACF plots
   - Lag structure analysis

6. **Volatility and Risk**:
   - Rolling standard deviation
   - Value at Risk (optional)

## 📌 Key Learnings

Through this project, I deepened my understanding of:
- How log returns behave over time
- Why stationarity is important for modeling
- How to prepare financial time series for forecasting

## 📷 Example Plot

![Log Return Plot](https://your-image-link-if-any.png)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
