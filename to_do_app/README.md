# Persistent To-Do App (Tkinter + PostgreSQL)

## 📌 Project Overview
A desktop Task and To-Do list management application built with **Tkinter** and backed by a local **PostgreSQL** database for complete data persistence.

---

## ✨ Features
- **CRUD Operations**: Add tasks, view task details, update records, and delete finished tasks.
- **Relational Storage**: Stores task title, detailed description, and due date in a PostgreSQL table (`tasks`).
- **Input Validation**: Verifies date formats (`YYYY-MM-DD`) and non-empty form fields.
- **Automated Schema Initialization**: Automatically runs `CREATE TABLE IF NOT EXISTS` upon launch.

---

## 📦 Requirements & Installation
Install the PostgreSQL database adapter:

```bash
pip install -r requirements.txt
```

### Dependencies
- `psycopg2-binary` - PostgreSQL database driver for Python
- Python standard library: `tkinter`, `datetime`

---

## 🗄️ Database Setup
1. Ensure PostgreSQL server is running.
2. Create the target database:
   ```sql
   CREATE DATABASE py_todo;
   ```
3. Update connection credentials in `to_do_app.py` if your database user/password differs from `postgres / admin`.

---

## 🚀 How to Run
Execute the application:

```bash
python to_do_app.py
```
