# Credit Approval System (Django)

## What this is
A demo Django project that imports customer & loan Excel files and evaluates credit approvals automatically.
APIs:
- GET /api/customers/
- POST /api/customers/import_data/  -> imports Excel files into DB and schedules evaluation
- GET /api/loans/
- GET /api/approvals/
- POST /api/approvals/evaluate/  -> schedule evaluation

Background tasks are handled via Django-Q using the ORM (no Redis needed).

## Requirements
- Python 3.9+ installed on Windows
- Git (optional)

## Setup (Windows)
1. Open PowerShell or CMD in this project folder (where `manage.py` sits).

2. Create virtual environment:
