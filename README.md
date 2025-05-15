# ✅ To-Do Website

A basic task management web application built with Django. It allows users to create, update, and delete to-do items. This project demonstrates how to build a simple CRUD (Create, Read, Update, Delete) app using Django’s Model-View-Template (MVT) architecture.

---

## 🚀 Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- View a list of all to-do items
- View a list of all items done
- Admin panel access

---

## 🛠️ Tech Stack

- **Backend:** Python3, Django
- **Frontend:** HTML5, CSS3, Bootstrap
- **Database:** SQLite (default in Django)
- **Environment management:** `.env` variables

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/to_do_website.git
cd to_do_website

### 2. Set up a virtual environment (optional but recommended):
```
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install dependencies:
```
pip install -r requirements.txt
```

### 4. Set up environment variables:
Create a .env file in the root directory of your project.

### 5. Apply migrations:
```
python manage.py migrate
```

### 6. Run the development server:
```
python manage.py runserver
```

### 7. Access the app:
```
http://127.0.0.1:8000/
```

---

## 🗒️ Notes
To access the Django admin, create a superuser:
```
python manage.py createsuperuser
```
And go to:
```
http://127.0.0.1:8000/admin/
```
