# Random Quote Generator (Tkinter + SQLAlchemy + PostgreSQL)

## 📌 Project Overview
A desktop application built with Python Tkinter that connects to a **PostgreSQL** database using the **SQLAlchemy ORM** to store and display inspirational quotes at the click of a button.

---

## ✨ Features
- **SQLAlchemy ORM Integration**: Automatic database table schema creation (`quotes`) and declarative mapping.
- **Persistent Seed Data**: Pre-populates the database with famous inspirational quotes.
- **Randomized UI**: Tkinter interface featuring a "Next quote" button that samples random quotes from PostgreSQL.

---

## 📦 Requirements & Installation
Install the required database packages:

```bash
pip install -r requirements.txt
```

### Dependencies
- `SQLAlchemy` - Python SQL toolkit and Object-Relational Mapper
- `psycopg2-binary` - PostgreSQL database adapter
- Python standard library: `tkinter`, `random`

---

## 🗄️ Database Setup
Ensure PostgreSQL is running locally:
1. Create a PostgreSQL database named `sqlalchemy`:
   ```sql
   CREATE DATABASE sqlalchemy;
   ```
2. Check/update database credentials in `06_random_quote.py` if needed (default: `postgresql+psycopg2://postgres:admin@localhost/sqlalchemy`).

---

## 🚀 How to Run
Run the application script:

```bash
python 06_random_quote.py
```
Click **Next quote** to fetch and display random inspirational thoughts!
