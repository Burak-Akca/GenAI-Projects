# Project Name

This document explains how to set up and run the project locally on both Windows and Linux/macOS systems.

---

## 1. Clone the Repository

```bash
git clone https://github.com/Burak-Akca/GenAI-Projects.git
cd GenAI-Projects
```

---

## 2. Create and Activate Virtual Environment

### Windows

```powershell
# Create virtual environment
python -m venv venv

# Activate virtual environment
.\venv\Scripts\activate

# To deactivate
deactivate
```

### Linux / macOS

```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate

# To deactivate
deactivate
```

---

## 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---


**Note:** This project is tested with Python 3.x.
