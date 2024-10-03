# Desktop Currency Converter (Tkinter + NBP API)

## 📌 Project Overview
A desktop GUI currency converter that retrieves live foreign exchange rates from the **National Bank of Poland (NBP) API** and performs real-time conversions from Polish Złoty (PLN) to major world currencies including **USD, EUR, and GBP**.

---

## ✨ Features
- Live API integration fetching current Table A exchange rates.
- Real-time keystroke conversion (updates target currencies as you type).
- Built with Python Tkinter and TTK themed widgets.

---

## 📦 Requirements & Installation
Install the required HTTP library:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - HTTP client to query the NBP exchange rates API
- Python standard library: `tkinter`, `ttk`, `time`

---

## 🚀 How to Run
Execute the Python script:

```bash
python currency_converter_nbp_api.py
```
Type an amount in PLN into the entry box to see instant conversion results.
