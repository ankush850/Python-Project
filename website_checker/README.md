# Live Website Uptime Checker (Tkinter + Multi-threading)

## 📌 Project Overview
A desktop GUI application that continuously monitors the availability, uptime status, and response latency of websites in real time using background worker threads.

---

## ✨ Features
- **Concurrent Monitoring**: Background daemon thread periodically pings registered URLs without freezing the Tkinter user interface.
- **Dynamic URL Management**: Add new website endpoints at runtime via the entry input.
- **Real-time Status Feed**: Displays status code (e.g., `200 OK`, `404 Not Found`), response latency in seconds, and timestamp of the last check.

---

## 📦 Requirements & Installation
Install the HTTP library:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - Sends HTTP GET requests to target endpoints
- Python standard library: `tkinter`, `threading`, `time`, `datetime`

---

## 🚀 How to Run
Run the application script:

```bash
python website_checker.py
```
Type any URL (e.g. `https://github.com`) in the top entry field and click **Add Website** to start monitoring.
