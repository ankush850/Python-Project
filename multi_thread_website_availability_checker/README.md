# Multi-Thread Website Availability Checker

## 📌 Project Overview
A high-performance multi-threaded Python application designed to verify the uptime and HTTP availability of a list of websites in parallel.

The application reads target URLs from `websites.txt`, spawns worker threads with mutex locking (`threading.Lock`), validates URL syntax, makes HTTP GET requests, and writes the consolidated status report to `report.txt`.

---

## ✨ Features
- **Concurrent Worker Threads**: Multiple worker threads (`Client`) run in parallel to process batches of URLs rapidly.
- **Thread Synchronization**: Thread-safe queue indexing using `threading.Lock` to avoid race conditions.
- **URL Validation**: Employs `validators` to sanitize URLs before network requests.
- **Automated Reporting**: Generates a clean output summary `report.txt` with HTTP status codes.

---

## 📦 Requirements & Installation
Install the project dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - HTTP request handling and response status verification
- `validators` - URL format syntax validation
- Python standard library: `threading`, `os`, `sys`

---

## 🚀 How to Run
1. Edit or populate the list of target websites in `websites.txt` (one domain/URL per line).
2. Execute `main.py`:
   ```bash
   python main.py
   ```
3. Check the generated `report.txt` for status codes.
