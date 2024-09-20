# Simple Desktop Text Editor (PySide6 / Qt)

## 📌 Project Overview
A clean desktop text editor application built with **PySide6 (Qt for Python)**. It provides a multi-line editing interface along with a native toolbar to open, edit, and save text documents on your local file system.

---

## ✨ Features
- **File Dialogs**: Open (`.txt` or any format) and save files using native Qt file dialogs (`QFileDialog`).
- **Main Toolbar**: Quick access toolbar buttons for file operations.
- **Interactive Editing**: Full text manipulation powered by `QTextEdit`.

---

## 📦 Requirements & Installation
Install the required PySide6 package:

```bash
pip install -r requirements.txt
```

### Dependencies
- `PySide6` - Python Qt framework
- Python standard library: `sys`, `os`

---

## 🚀 How to Run
Launch the application:

```bash
python simple_text_editor.py
```
Use the **Open** button to browse and load a file, type your text in the central area, and click **Save** to persist changes.
