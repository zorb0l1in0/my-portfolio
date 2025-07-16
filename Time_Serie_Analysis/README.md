# 📈 Time Series Analysis of Log Returns

This project presents a detailed analysis of financial time series data using the Log Return method. The analysis aims to provide insights into the behavior of asset returns, volatility patterns, and their statistical properties through univariate, multivariate, and panel data approaches.


## 🧭 Overview

The project focuses on:

* Calculating and interpreting Log Returns.
* Conducting exploratory data analysis (EDA) to understand data distribution, trends, and patterns.
* Implementing statistical tests for stationarity.
* Visualizing volatility clustering in financial returns.
* Modeling return series using statistical methods such as ARIMA/GARCH.

## 🧱 Project Structure

The analysis is organized into clear, sequential steps:

1. **Data Loading and Preprocessing**: Initial handling, cleansing, and processing of raw financial data.
2. **Exploratory Data Analysis (EDA)**: Descriptive statistics and visualization to understand underlying patterns.
3. **Log Return Computation**: Calculation and interpretation of log returns.
4. **Stationarity Tests**: Statistical methods (e.g., Augmented Dickey-Fuller test) to confirm time series properties.
5. **Volatility Analysis**: ARCH effects, GARCH modeling, and heteroskedasticity tests.
6. **Modeling and Forecasting**: Application of ARIMA, SARIMAX, GARCH, PanelOLS, and ML models for forecasting.
7. **Evaluation**: Metrics like RMSE, MAE, R², accuracy, F1-score.


## 🛠️ Tools and Technologies

### 📊 Data Analysis & Visualization
- **pandas**, **numpy** – Data handling and computation  
- **matplotlib**, **seaborn** – Static and statistical plots  
- **tqdm** – Progress bars for loops

### 📈 Time Series Modeling
- **statsmodels** – ARIMA, SARIMAX, VAR, Granger causality, ADF test, Ljung-Box, heteroskedasticity tests  
- **arch** – GARCH models for volatility

### 🧪 Statistical Tests
- **scipy.stats** – Normality tests (Jarque-Bera, kurtosis, skewness, t-test)

### 🤖 Machine Learning
- **scikit-learn** – Random Forest, Isolation Forest, Logistic Regression, model selection (`GridSearchCV`, `TimeSeriesSplit`), standardization, metrics  
- **xgboost** – Gradient Boosted Models (regression and classification)

### 🔄 Online Learning & Drift Detection
- **river** – Stream-based ML models, preprocessing, concept drift detection (ADWIN)

### 🧩 Panel Data Modeling
- **linearmodels** – `PanelOLS` for fixed-effects regression on panel data

### ⚙️ Utilities
- **joblib** – Parallel processing  
- **itertools.product** – Grid search setup  
- **warnings** – Warning control


## 🔄 How to Use

* Clone or download the repository.
* Install dependencies listed above.
* Run the Jupyter notebook provided to reproduce analysis steps and visualizations.

## 💡 Insights and Results

* Demonstrated volatility clustering indicating periods of high and low volatility.
* Verified stationarity in the log return series, critical for modeling and forecasting.
* Provided robust models (ARIMA/GARCH) to forecast returns and volatility effectively.

## 🎯 Applications

This analysis is particularly useful for:

* Traders and investors looking to understand risk and return dynamics.
* Financial analysts conducting market risk assessments.
* Researchers studying financial market behavior.

## 👤 Author

* \[Francesca Tuninetti]
* \[www.linkedin.com/in/tuninettifrancesca]

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
