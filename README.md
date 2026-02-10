# 📈 Stock Comparison Analysis

## Overview
**Stock Comparison Analysis** is a Python-based financial analytics project that performs a comparative study of two publicly traded companies—Amazon (AMZN) and Google (GOOGL). The project analyzes stock performance over a selected time period using real market data and applies quantitative financial metrics to evaluate returns, risk, and market sensitivity.

---

## Project Objectives
- Fetch real-time and historical stock market data
- Analyze and compare daily stock returns
- Evaluate cumulative returns over the selected period
- Measure and compare stock volatility
- Calculate Beta values against a market benchmark
- Visualize financial insights using interactive charts

---

## Tech Stack & Libraries
- **Python 3**
- **yfinance** – Stock market data extraction
- **pandas** – Data processing and financial calculations
- **plotly** – Interactive data visualization

---

## Data Source
- Stock price data retrieved from **Yahoo Finance**
- Market benchmark used: **S&P 500 Index (^GSPC)**

---

## Methodology
1. **Data Collection**
   - Historical price data for Amazon and Google is fetched for the specified time range.
2. **Daily Return Calculation**
   - Daily percentage returns are computed using adjusted closing prices.
3. **Cumulative Return Analysis**
   - Overall growth performance is evaluated using cumulative returns.
4. **Volatility Analysis**
   - Risk is quantified using the standard deviation of daily returns.
5. **Beta Calculation**
   - Market sensitivity is measured using covariance with the S&P 500 index.
6. **Visualization**
   - Interactive line and bar charts are generated for clear financial insights.

---

## Key Features
- Comparative analysis of two major technology stocks
- Interactive visualizations for better interpretation
- Risk and return evaluation using financial metrics
- Market benchmark comparison using Beta analysis

---

## Output Visualizations
- Daily Returns Comparison (Line Chart)
- Cumulative Returns Comparison (Line Chart)
- Volatility Comparison (Bar Chart)

---

## Results & Insights
- Identifies relative performance trends between Amazon and Google
- Highlights volatility differences to assess investment risk
- Determines market sensitivity using Beta values
- Provides data-driven conclusions based on quantitative analysis

---

## How to Run the Project

### Prerequisites
Ensure Python 3 is installed on your system.

### Installation
```bash
pip install yfinance pandas plotly
```

### Execution

1. Open the Jupyter Notebook
2. Run all cells sequentially
3. Interactive charts will be displayed inline
