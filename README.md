# 🏆 Time Series Forecasting of Monthly Gold Prices

> 📌 Predicting the future by understanding the past – A data-driven exploration into gold price trends

---

## 📘 Project Overview

Gold has always been considered a stable and valuable commodity. Predicting its price trends can provide useful insights for investors, traders, and economic analysts. In this project, we perform **time series forecasting** on historical **monthly gold prices** using statistical modeling techniques.

Our goal is to understand underlying trends, seasonal patterns, and predict future prices using the **ARIMA (AutoRegressive Integrated Moving Average)** model.

---

## 🧠 Objectives

- Load, clean, and preprocess monthly gold price data  
- Visualize trends, seasonality, and stationarity  
- Identify optimal ARIMA parameters using ACF, PACF, and grid search  
- Train the ARIMA model and forecast future gold prices  
- Evaluate model performance using RMSE and visual plots  
- Present forecast results with clear and interpretable visualizations

---

## 📁 Dataset

- **File**: `gold_monthly_csv.csv`
- **Description**: Contains monthly average gold prices
- **Features**:  
  - `Date` (Month/Year)  
  - `Price` (Gold Price in selected currency)
- **Source**: *(Add link or name of dataset provider if available)*

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** | Primary programming language |
| **Pandas** | Data loading and manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib & Seaborn** | Data visualization |
| **Statsmodels** | Time series modeling (ARIMA) |
| **scikit-learn** | Error evaluation (RMSE) |
| **Jupyter Notebook** | Interactive code environment |

---

## 📊 Exploratory Data Analysis (EDA)

- **Trend Analysis**: Used line plots to detect long-term trends
- **Stationarity Check**: Augmented Dickey-Fuller (ADF) test
- **Seasonality Decomposition**: Visualized components using seasonal decomposition
- **Rolling Mean & Std Dev**: Identified if time series is stationary
- **ACF & PACF**: Determined `p`, `d`, `q` values for ARIMA

---

## 🔮 Forecasting Approach

We used **ARIMA modeling** due to its strength in forecasting stationary time series data.

### ✅ Steps Followed:
1. Made the series stationary using differencing
2. Plotted ACF and PACF to determine lag values
3. Tuned ARIMA parameters (`p`, `d`, `q`)
4. Trained model on historical data
5. Forecasted prices for upcoming months
6. Evaluated model using RMSE and plotted predicted vs actual prices

---

## 📈 Results

- The model performed well with minimal error margin
- Forecast plot showed continuity with actual trends
- RMSE provided a quantifiable measure of accuracy


```python
from matplotlib import pyplot as plt
plt.plot(actual, label="Actual Prices")
plt.plot(predicted, label="Forecasted Prices")
plt.title("Gold Price Forecast")
plt.legend()
plt.show()
```


# 🧪 Model Evaluation
Evaluation Metric: Root Mean Squared Error (RMSE)

Why RMSE: Penalizes larger errors more than smaller ones

Interpretation: Lower RMSE indicates better prediction accuracy


# ▶️ How to Run the Project

1. Clone the repository
   git clone https://github.com/yourusername/gold-price-forecasting.git
cd gold-price-forecasting

2.Open the notebook
  jupyter notebook Time_Series_Forecasting.ipynb

3.Install requirements (if needed)
  pip install -r requirements.txt

4.Run all cells and explore the forecast!


# 💡 Key Learnings

Hands-on implementation of ARIMA for time series data

Real-world financial data modeling

Importance of stationarity and hyperparameter tuning

Interpretation of forecasting outcomes

# 🤝 Let's Connect!

💼 LinkedIn – www.linkedin.com/in/vikas-ku

📧 Email: vk328696@gmail.com







