# B2SMatch: Contrastive Learning for Binary-Source Code Similarity Detection

## 📋 Project Overview
B2SMatch is a Django-based system for binary similarity analysis and vulnerability detection with deep learning (ASM2VEC/BERT) and contrastive learning.

### Core Features
- 🔍 Binary similarity analysis (ELF/PE)
- 🛡️ Vulnerability detection with CWE reporting
- 📊 Analysis report management (history/export)

## 💻 System Requirements for Model Training
- Python 3.8+
- 8GB+ RAM
- CUDA support (recommended for GPU acceleration)
- Modern browsers (Chrome 90+/Firefox 88+/Edge 90+)

## 🖥️ System Interface
- 💌 User Registration
  ![Login - B2SMatch](PNG/Login%20-%20B2SMatch.png)

- 🏠 Home Page
  ![Dashboard - B2SMatch](PNG/Dashboard%20-%20B2SMatch.png)

- 🔍 Binary Similarity Analysis
  ![Binary Code Function Comparison - B2SMatch](PNG/Binary%20Code%20Function%20Comparison%20-%20B2SMatch.png)

- 🛡️ Vulnerability Detection
  ![Vulnerability Function Similarity Analysis - B2SMatch](PNG/Vulnerability%20Function%20Similarity%20Analysis%20-%20B2SMatch.png)

- ⚙️ Admin Interface
  ![Admin Dashboard - B2SMatch](PNG/Admin%20Dashboard%20-%20B2SMatch.png)
  ![Update Analysis Model - B2SMatch](PNG/Update%20Analysis%20Model%20-%20B2SMatch.png)

## 🚀 Quick Start

### 1. Environment Setup
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### 2. System Configuration
```bash
# Enter Django project directory (manage.py is here)
cd bin2src_system

# Initialize database
python manage.py migrate

# Create admin account
python manage.py createsuperuser
```

### 3. Launch Service
```bash
# Development environment
python manage.py runserver
```

## 📄 License
This project is licensed under the MIT License. See the [LICENSE] file for details. 
