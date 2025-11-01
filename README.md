# 💳 Credit Approval System (Django + REST Framework)

A full-stack **credit approval system** built using **Python Django**, **Django REST Framework**, and **Django-Q** for background processing.

This project analyzes customer loan histories and new transactions to automatically **approve or reject credit applications**.

---

## 🚀 Features

- Import customer and loan data from Excel files (`data_files/`)
- RESTful API endpoints for:
  - Customers
  - Loans
  - Credit approvals
- Background job processing with **Django-Q**
- Fully documented API using **DRF browsable interface**
- Ready for deployment or Docker use

---

## 🛠️ Tech Stack

- Python 3.10+
- Django 5.0
- Django REST Framework
- Django-Q (for async background tasks)
- Pandas + OpenPyXL (for Excel data import)

---

## ⚙️ Installation (Windows)

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/credit_approval_system.git
   cd credit_approval_system
