# E-Commerce Shopping Cart (Object-Oriented Programming)

## 📌 Project Overview
A modular Python simulation of an e-commerce shopping cart system, highlighting core **Object-Oriented Programming (OOP)** principles: Encapsulation, Inheritance, and Polymorphism.

---

## 🏗️ Architecture & Class Design
- **`Product` (`products.py`)**: Base class managing item name, price, and unique ID generation.
- **`TV` / `Phone` (`products.py`)**: Specialized subclasses inheriting from `Product` with unique attributes (screen size, color).
- **`Cart` (`cart.py`)**: Cart manager that encapsulates product items, dynamically computes total order value, and prints itemized receipts.
- **`main.py`**: Driver script demonstrating product instantiation, adding items to the cart, and printing final checkout calculations.

---

## 📦 Requirements & Installation
This project runs entirely on the **Python Standard Library** and requires no third-party packages.

---

## 🚀 How to Run
Execute the main script:

```bash
python main.py
```
