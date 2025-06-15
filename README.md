#  Project 1: Simple Stock EDA — Reliance Industries

Explore and analyze stock price data using Exploratory Data Analysis (EDA), returns computation, and visualizations.

---

# Objective

Understand the historical performance of Reliance Industries stock (RELIANCE.NS) by exploring:
- Price trends
- Daily and cumulative returns
- Volatility behavior
- Trend indicators like Simple Moving Averages (SMA)

---

# 5-Step Process

# 1. Define the Question
> How has Reliance stock performed over the years?  
> What patterns exist in price, returns, and volatility?

# 2. Collect the Data
- Fetched data using the [`yfinance`](https://pypi.org/project/yfinance/) API  
- Stock: `RELIANCE.NS`  
- Date Range: 2018–2024

# 3. Clean the Data
- Removed missing values (NaNs)
- Created new columns:
  - Daily Return
  - Cumulative Return
  - Rolling Volatility
  - SMA (50-day and 200-day)

# 4. Analyze the Data
- Summary statistics (`.describe()`)
- Yearly & monthly average returns
- Detection of high-volatility periods
- SMA crossover patterns

### 5. Visualize and Share Findings

| Description |
|-------|-------------|
|Closing Price| Tracks stock movement over time |
|Daily Return| Shows distribution of daily returns |
|Cumulative Return| Visualizes long-term investment growth |
|Rolling Volatility| Highlights risk fluctuations |
|SMA Plot| Shows trends via 50-day & 200-day moving averages |

---

#  Sample Visuals

>  These are static versions of interactive charts for GitHub compatibility.

<img src="Reliance_daily_return.png" width="600">
<img src="'moving average.png" width="600">

>  **Interactive Plotly graphs don't render on GitHub.**  
> Open the notebook in [NBViewer](https://nbviewer.org/) or run it locally to see interactive charts.

---



## Getting Started

## 1. Clone the repository
```bash
git clone https://github.com/SP56775/stock_analysis.git
cd stock_analysis
