# My Quantitative Finance Learning Path

## Introduction
This repository is my learning roadmap to becoming a quantitative dev by leveraging Python skills in financial data analysis, statistics, and algorithmic trading.

## Learning Roadmap

### **1. Mastering Pandas & NumPy for Financial Data**
#### 📌 Exercise: Stock Data Cleaning & Feature Engineering
#### 🔍 Goal: Learn how to manipulate time-series stock data efficiently.

#### **Tasks:**
- Download stock data using `yfinance`.
- Compute daily & monthly returns.
- Implement rolling statistics (moving average, volatility).
- Handle missing data.
- Compute correlation between stocks.

#### **Resources:**
- [Pandas Official Documentation](https://pandas.pydata.org/docs/)
- [Python for Data Analysis](https://wesmckinney.com/book/)
- [Kaggle Pandas Tutorial](https://www.kaggle.com/learn/pandas)

---

### **2. Statistical Analysis with SciPy & Statsmodels**
#### 📌 Exercise: Detecting Mean-Reverting Stocks
#### 🔍 Goal: Use statistical tests to identify mean-reverting assets.

#### **Tasks:**
- Understand mean reversion and stationarity.
- Conduct an **Augmented Dickey-Fuller (ADF) test**.
- Identify cointegrated stock pairs using Engle-Granger test.
- Implement OLS regression for factor exposure.

#### **Resources:**
- [Statsmodels Documentation](https://www.statsmodels.org/stable/index.html)
- [QuantStart: ADF Test for Mean Reversion](https://www.quantstart.com/articles/Basics-of-Statistical-Mean-Reversion-Testing/)
- *Quantitative Trading* by Ernest Chan

---

### **3. Data Visualization with Matplotlib & Seaborn**
#### 📌 Exercise: Visualizing Market Trends
#### 🔍 Goal: Create effective plots for financial data analysis.

#### **Tasks:**
- Plot time-series stock data.
- Implement moving average visualization.
- Create heatmaps to analyze stock correlations.
- Plot return distributions using histograms & KDE.

#### **Resources:**
- [Matplotlib Guide](https://matplotlib.org/stable/tutorials/introductory/pyplot.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

---

### **4. Backtesting with TA-Lib & Backtrader**
#### 📌 Exercise: Backtesting a Simple RSI Strategy
#### 🔍 Goal: Implement and test a **technical trading strategy**.

#### **Tasks:**
- Compute RSI using `TA-Lib`.
- Define trading rules (RSI < 30 Buy, RSI > 70 Sell).
- Implement strategy in `Backtrader`.
- Evaluate performance using Sharpe ratio and max drawdown.

#### **Resources:**
- [Backtrader Documentation](https://www.backtrader.com/docu/)
- [TA-Lib Indicators Guide](https://mrjbq7.github.io/ta-lib/)
- *Algorithmic Trading* by Ernest Chan

---

### **5. Vectorized Backtesting with Pandas & NumPy**
#### 📌 Exercise: Building a Vectorized Momentum Strategy
#### 🔍 Goal: Develop a **fast, loop-free backtesting system**.

#### **Tasks:**
- Use `np.where()` to generate trading signals.
- Compute log returns efficiently.
- Implement portfolio performance metrics (Sharpe Ratio, Max Drawdown).

#### **Resources:**
- [Fast Vectorized Backtesting](https://www.quantstart.com/articles/Vectorised-Backtesting-in-Pandas/)
- *Advances in Financial Machine Learning* by López de Prado

---

## **Final Capstone Project: Full Quant Trading Strategy**
### 📌 Goal: Develop a full **quantitative trading system**, including:
1. **Strategy Design** – Define entry/exit rules.
2. **Backtesting** – Use vectorized or `Backtrader`.
3. **Performance Evaluation** – Sharpe ratio, max drawdown.
4. **Optimization** – Test different parameter settings.

### 📌 **Bonus Task:** Paper Trading
- Deploy your strategy on `Interactive Brokers` or `Alpaca`.

#### **Resources:**
- [QuantConnect](https://www.quantconnect.com/)
- [Alpaca API](https://alpaca.markets/docs/)

---

## **Weekly Plan**
| Week | Focus |
|------|-----------------------------------|
| 1-2  | Pandas, NumPy for financial data |
| 3-4  | Statistics & hypothesis testing  |
| 5-6  | Backtesting & strategy building  |
| 7+   | Capstone project & real trading  |

---



