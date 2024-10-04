# Stock Market Information Dashboard (Tkinter + yfinance)

## 📌 Project Overview
A desktop market intelligence application built with Python **Tkinter** and the **Yahoo Finance (`yfinance`)** API. Users can input any stock ticker symbol (e.g., `AAPL`, `MSFT`, `TSLA`, `GOOG`) to view real-time company fundamentals, valuation multiples, and business profiles.

---

## ✨ Features
- Fast stock ticker lookup via Yahoo Finance.
- Formatted display of key financial metrics:
  - Market Cap, Forward P/E, Dividend Yield
  - 52-Week High/Low, Beta, Volume
  - Business Summary & Sector / Industry classification
- Scrollable text UI with auto-clearing and search event triggers.

---

## 📦 Requirements & Installation
Install the required Yahoo Finance library:

```bash
pip install -r requirements.txt
```

### Dependencies
- `yfinance` - Market data downloader from Yahoo! Finance
- Python standard library: `tkinter`

---

## 🚀 How to Run
Run the desktop app:

```bash
python stock_info_yfinance.py
```
Type any ticker in the input box and press **Enter** to download and display company intelligence.
