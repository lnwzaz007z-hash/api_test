# Django User API - Technical Assessment

A RESTful API built with Django and Django REST Framework (DRF) to manage user data. This project is developed as part of a technical test requirement, focusing on clean code architecture, data validation, and standard HTTP practices.

## 🛠️ Tech Stack

- Python 3.x
- Django
- Django REST Framework (DRF)
- SQLite3

## ⚙️ Installation & Setup

Follow these steps to get the project running on your local machine.

**1. Clone the repository**
```bash
git clone https://github.com/lnwzaz007z-hash/api_test.git
cd api_test
```

**2. Create and activate a virtual environment**

For Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```
For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```
**3. Install dependencies**
```bash
pip install -r requirements.txt
```
**4. Run database migrations**
```bash
python manage.py migrate
```
**5. Start the development server**
```bash
python manage.py runserver
```

The API will be available at http://127.0.0.1:8000/users.
