# Webpage Source Downloader & Archiver

## 📌 Project Overview
A command-line utility to validate, request, and download the full raw HTML contents of any target website, automatically saving the response as an organized archive file.

---

## ✨ Features
- **URL Validation**: Employs `validators` to sanitize URLs before network requests.
- **CLI Arguments**: Pass custom URLs directly via command-line arguments.
- **Directory Creation**: Automatically initializes local storage directories (`./websites`).
- **Archive Saving**: Saves raw HTTP response body to `.html` with metadata.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - HTTP library to fetch page contents
- `validators` - Validates URL formatting
- Python standard library: `os`, `sys`, `urllib.parse`, `datetime`

---

## 🚀 How to Run
Run with default URL (`https://google.com`):
```bash
python website_downloader.py
```

Or pass a specific URL:
```bash
python website_downloader.py https://python.org
```
Downloaded web files will be saved in the `websites/` folder.
