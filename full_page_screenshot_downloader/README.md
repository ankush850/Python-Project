# Full Page Screenshot Downloader (Selenium + Chrome WebDriver)

## 📌 Project Overview
An automated web scraper and browser automation utility that uses **Selenium WebDriver** and **webdriver-manager** to navigate to target websites in headless Chrome, execute interactions (such as searches), and capture high-resolution full-page screenshots.

---

## ✨ Features
- Automated Chrome WebDriver management (no manual binary downloads required).
- Headless execution (`--headless`) for background screenshot tasks.
- Element interaction (locates search inputs via XPath, submits queries, and takes screenshots).
- Dynamic JavaScript window resizing to match entire scrollable page height and width for seamless full-page screenshots.

---

## 📦 Requirements & Installation
Install Selenium and the WebDriver Manager:

```bash
pip install -r requirements.txt
```

### Dependencies
- `selenium` - Browser automation framework
- `webdriver-manager` - Automatic ChromeDriver download and cache manager
- Google Chrome browser installed on the host system

---

## 🚀 How to Run
Run the automation script:

```bash
python full_page_screenshot_downloader.py
```
Output images (`python.org.1.png`, `python.org.2.png`) will be saved in the project directory.
