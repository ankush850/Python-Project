# Stock Price Candlestick Chart (yfinance + Plotly)

## 📌 Project Overview
A financial visualization script that downloads historical daily stock price data (Open, High, Low, Close, Volume - OHLCV) using **`yfinance`** and renders high-quality interactive **Candlestick Price Charts** using **Plotly**.

---

## ✨ Features
- Downloads 6-month daily historical data directly from Yahoo! Finance.
- Renders interactive Plotly Candlestick charts (`go.Candlestick`).
- Interactive chart capabilities: Hover tooltips with exact price points, range selectors, zooming, and pan controls.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `yfinance` - Historical market data API
- `plotly` - Interactive charting and graphing library
- `pandas` - DataFrame restructuring and index management

---

## 🚀 How to Run
Execute the script:

```bash
python stock_info_yfinance_plotly.py
```
This opens the interactive candlestick chart directly in your default web browser. You can change the ticker variable (e.g., `TSLA`, `AAPL`, `NVDA`) directly in `stock_info_yfinance_plotly.py`.
