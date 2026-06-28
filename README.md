# 🗄️ Python Labs - ITI Course

Comprehensive Python laboratory exercises covering fundamentals, data structures, object-oriented programming, testing, web development (Django), and packaging.

## 📚 Lab Modules

| Lab               | Topics                                                                | Focus                                                  |
| ----------------- | --------------------------------------------------------------------- | ------------------------------------------------------ |
| **Django-Lab-01** | Django project structure, models, views, templates, CRUD (books app)  | Web development with Django (models, templates, forms) |
| **Django-Lab-02** | Django advanced features, static files, admin panel, forms validation | Web development with Django (admin, static files, styling) |
| **Django-Lab-04** | Django REST framework, API endpoints, serializers, views         | REST API development with Django (media services)       |
| **Lab-01**        | Python basics, data types, control flow, I/O — multiple small scripts | Fundamentals & syntax, practice exercises              |
| **Lab-02**        | Functions, collections, basic algorithms                              | Core programming patterns and problem-solving          |
| **Lab-05**        | Object-oriented programming, modules, simple persistence              | OOP design, modules, basic DB/file usage               |

## 📁 Repository Highlights

- Django app with a `books` app and simple CRUD views and templates.
- Lab scripts under `Lab-01/`, `Lab-02/`, and `Lab-05/` demonstrating increasing complexity from basics to OOP.

## 🚀 Quick Start

Run Python scripts from the workspace root. Example (Windows):

```powershell
# Check Python version
python --version

# Create and activate a virtual environment (Windows)
python -m venv venv
venv\Scripts\activate

# Run a lab script, e.g. Lab-01 exercises
python Lab-01/lab-01-01.py
```

## 🧰 Django Lab (quick)

To run the Django project locally:

```powershell
cd Django-Lab-01
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/ in your browser
```

## ✨ Requirements

- Python 3.8+
- pip
- virtualenv or venv

## 👤 Author

**Fares Hazem**

## 🎓 Course

Python - ITI
