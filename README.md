
# 🏆 Time Series Forecasting of Monthly Gold Prices

> 📈 Predicting the future by understanding the past – A time series forecasting project using ARIMA and financial data analytics.

---

## 📚 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 STAR-Based Summary](#-star-based-summary)
- [🧠 Objectives](#-objectives)
- [📁 Dataset](#-dataset)
- [🛠️ Tools & Technologies](#-tools--technologies)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🔮 Forecasting Approach](#-forecasting-approach)
- [📈 Results](#-results)
- [🧪 Model Evaluation](#-model-evaluation)
- [💻 How to Run the Project](#-how-to-run-the-project)
- [🧠 Key Skills Used](#-key-skills-used)
- [🔖 Keywords & Hashtags](#-keywords--hashtags)
- [💡 Key Learnings](#-key-learnings)
- [🙋‍♂️ Let's Connect](#-lets-connect)

---

## 📌 Project Overview

This project focuses on **predicting monthly gold prices** using historical data and time series forecasting techniques. Gold is a critical financial asset, and accurately modeling its price trends provides valuable insights for investors, traders, and analysts.

Using ARIMA-based modeling, we forecast short-term price movement and evaluate the model's performance using real metrics.

---

## 🎯 STAR-Based Summary

**S – Situation:**  
Gold prices are influenced by various global factors and exhibit seasonal trends. Accurate predictions are vital for risk management and financial planning.

**T – Task:**  
Build a reliable and interpretable forecasting model based on monthly gold prices.

**A – Action:**  
- Cleaned and transformed historical time-series data  
- Performed ADF tests, decomposition, and rolling statistics  
- Identified optimal ARIMA parameters via ACF & PACF  
- Trained, evaluated, and forecasted using ARIMA model

**R – Result:**  
- Forecasts aligned with real trends  
- RMSE used to measure accuracy  
- Delivered visualizations of actual vs predicted prices for stakeholder interpretation

---

## 🧠 Objectives

- Perform EDA on time-series gold price data  
- Detect trend, seasonality, and noise in price movement  
- Apply ARIMA to forecast future values  
- Evaluate predictions using RMSE  
- Build visuals for insights and interpretation

---

## 📁 Dataset

- **File:** `gold_monthly_csv.csv`  
- **Source:** Historical monthly gold prices *(add source link if public)*  
- **Columns:**  
  - `Date`: Monthly date  
  - `Price`: Average gold price for the month

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                             |
|-----------------|-------------------------------------|
| Python          | Programming language                |
| Pandas & NumPy  | Data handling & transformation      |
| Matplotlib & Seaborn | Visualization of trends & results |
| Statsmodels     | Time series modeling with ARIMA     |
| Scikit-learn    | RMSE calculation                    |
| Jupyter Notebook| Interactive development             |

---

## 📊 Exploratory Data Analysis

- ✅ **Trend Analysis** via line plots  
- ✅ **ADF Test** to test for stationarity  
- ✅ **Decomposition** to split data into trend, seasonality, and residuals  
- ✅ **ACF/PACF** plots to identify `p` and `q`  
- ✅ **Differencing** to stabilize variance and remove trend

---

## 🔮 Forecasting Approach

We applied the **ARIMA** model (AutoRegressive Integrated Moving Average), best suited for univariate time series forecasting.

### 🚀 Steps Taken:
1. Preprocessed and differenced time series  
2. Conducted ADF test to confirm stationarity  
3. Plotted ACF/PACF to determine lags  
4. Tuned (p,d,q) values  
5. Forecasted future prices  
6. Compared forecast vs actual using visual plots and RMSE

---

## 📈 Results

- The ARIMA model captured historical trends accurately  
- Forecasts extended several months ahead  
- Predictions followed real price patterns with minimal deviation  

### 📊 Sample Output:
```python
plt.plot(actual, label="Actual Prices")
plt.plot(predicted, label="Forecasted Prices")
plt.title("Gold Price Forecast")
plt.legend()
plt.show()
```
### 🧪 Model Evaluation
Metric Used: Root Mean Squared Error (RMSE)

Interpretation: Lower RMSE = more accurate forecast

Goal: Minimize forecasting error over time

### 💻 How to Run the Project

Copy code
# Clone the repository
git clone https://github.com/yourusername/gold-price-forecasting.git
cd gold-price-forecasting

# Open the Jupyter Notebook
jupyter notebook Time_Series_Forecasting.ipynb

# (Optional) Install required libraries
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
## 🧠 Key Skills Used

📈 Time Series Analysis & Stationarity Testing

🔄 ARIMA/SARIMA Modeling

🧪 Model Tuning and Evaluation

📊 Data Visualization

🧹 Data Cleaning & Preprocessing

## 🔖 Keywords & Hashtags
Keywords:
Time Series Forecasting, Gold Price Prediction, ARIMA Model, Financial Data Analysis, Python, RMSE, ADF Test, Rolling Mean, Decomposition, ACF, PACF

Hashtags:
#TimeSeries #GoldForecast #PythonForFinance #ARIMA #ForecastingModel #DataScienceProject
#GitHubPortfolio #VikasKumarProjects #FinancialAnalytics

## 💡Key Learnings
Understanding time-series assumptions and stationarity

End-to-end implementation of ARIMA

Real-world application to financial datasets

Importance of error metrics in predictive modeling

### 🙋‍♂️ Let's Connect

📧 Email: vk328696@gmail.com

🔗 LinkedIn: linkedin.com/in/vikas-ku

📂 GitHub: github.com/vikasgit101

⭐ If you liked this project, feel free to star the repo and connect on LinkedIn!
