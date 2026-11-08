# 📊 Expense Tracker App (Django + EasyOCR)

A clean, full-stack personal finance web application built with **Django**, **Bootstrap 5**, and **EasyOCR**. It allows users to track income and expenses, scan physical receipts automatically, monitor monthly category budgets with live alerts, and visualize financial statistics.

---

## ✨ Features

* **🔐 User Authentication:** Registration, sign-in, and sign-out functionality with auto-creation of default categories.
* **📈 Interactive Dashboard:** Real-time expense breakdown chart powered by **Chart.js**.
* **🧾 Receipt OCR Scanning:** Automatic text extraction from receipt images using **EasyOCR** to auto-fill amount and date fields.
* **🎯 Monthly Budgeting:** Category-based limits with visual progress bars and overspending warnings.
* **📁 Category Management:** Add, edit, and delete income or expense categories dynamically.
* **📥 CSV Data Export:** One-click downloadable report (`utf-8-sig` compatible with MS Excel).

---

## 🛠️ Tech Stack

* **Backend:** Python 3.10+, Django 4.2+
* **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript (ES6+), Chart.js
* **OCR & Computer Vision:** EasyOCR, OpenCV
* **Database:** SQLite (Development) / PostgreSQL (Production ready)

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally on your machine.

### Prerequisites

* Python 3.10 or higher installed on your system.
* Git installed.

### 1. Clone the Repository

```bash
git clone [https://github.com/YOUR_USERNAME/django-expense-tracker.git](https://github.com/YOUR_USERNAME/django-expense-tracker.git)
cd django-expense-tracker
