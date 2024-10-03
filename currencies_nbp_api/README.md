# NBP Currencies CLI (National Bank of Poland API)

## 📌 Project Overview
A command-line interface (CLI) application that queries the official **National Bank of Poland (NBP) Web API** to fetch current foreign exchange rates for Table A (major foreign currencies against Polish Złoty - PLN).

---

## ✨ Features
- Sends HTTP GET requests to `http://api.nbp.pl/api/exchangerates/tables/a/?format=json`.
- Parses returned JSON structure into currency names and their mid-exchange rates (`mid`).
- Includes reference API response schema in `NBP_response_format.json`.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - HTTP library to consume the REST API

---

## 🚀 How to Run
Run the script from your terminal:

```bash
python currencies_nbp_api.py
```
