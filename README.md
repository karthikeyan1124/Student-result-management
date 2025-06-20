# Student Result Management System 🎓

A simple Python-based Student Result Management System to manage student records, subjects, and generate reports using a friendly interface.

## 🛠️ Features

- User Registration & Login
- Student Management
- Subject Management
- Result Entry & Management
- View and Generate Reports
- SQLite database (`SRMS.db`)

## 📂 Project Structure

create_db.py # Script to create database schema
dashboard.py # Main dashboard interface
login.py # User login functionality
register.py # User registration
report.py # Generate reports
result.py # Manage results
student.py # Manage student records
subject.py # Manage subjects
SRMS.db # SQLite database file

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- SQLite3 (comes with Python)
- Required libraries in `requirements.txt`

### Installation

1. Clone this repository:

```bash
git clone https://github.com/karthikeyan1124/STUDENT-RESULT-MANAGEMENT-SYSTEM.git
cd STUDENT-RESULT-MANAGEMENT-SYSTEM
Create a virtual environment:

```bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

```bash

pip install -r requirements.txt

Running the App

python login.py
or
python dashboard.py
