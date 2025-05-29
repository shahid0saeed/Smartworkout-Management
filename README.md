# 🛒 Smart Mart Management System

A Python-based GUI application built with **Tkinter** that helps manage small retail marts with role-based dashboards for Admin and Cashier. This system follows the **MVC + N-Tier architecture**, storing data in `.txt` files and supporting exception handling, unit testing, and executable deployment.

---

## 📁 Folder Structure

smart_mart/
│
├── main.py # Entry point
├── models/ # Data handling
│ └── user_model.py
├── controllers/ # Business logic
│ └── login_controller.py
├── views/ # GUI screens
│ ├── login_view.py
│ ├── admin_view.py
│ └── cashier_view.py
├── data/ # Storage files
│ ├── admin.txt
│ ├── cashiers.txt
│ ├── products.txt
│ └── bills.txt
├── logs/ # Error logs
│ └── error.log
├── tests/ # Unit tests
│ └── test_user_model.py
├── README.md # Documentation



---

## 🧑‍💻 Features

### 👨‍💼 Admin
- Secure login
- Add products (name, category, price, stock)
- View product list
- View billing history

### 🧾 Cashier
- Secure login
- Search and add products to cart
- Generate total bill
- Save bill record to file

### ✅ General
- Built with Tkinter GUI
- MVC + N-Tier architecture
- Exception handling with logging
- Unit testing using `pytest`
- `.exe` file creation via `PyInstaller`

---

## 🚀 Getting Started

### 🔧 Requirements
- Python 3.x
- `pytest`
- `pyinstaller` (for .exe)

### ▶️ Run the Application
```bash
python main.py
