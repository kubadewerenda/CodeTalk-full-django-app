# 💬 CodeTalk – Full Django Forum App

**CodeTalk** is a full-featured discussion forum for developers, built entirely with Django. The platform allows users to create accounts, post topics, reply to threads, and browse conversations based on topics. It was developed as a larger project to practice and demonstrate skills in Django, templating, authentication, and data modeling.

This app simulates a real-world developer forum – simple, focused, and extensible.

---

## ✨ Features

- 🧑‍💻 User registration and login (with Django auth)
- 🧵 Topic creation, viewing, and deletion (permissions controlled)
- 💬 Replies to topics
- 🏷️ Topics-based filtering and navigation
- 🔍 Search functionality (optional, if implemented)
- 🖼️ Clean, responsive UI using Django templates

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Django templates
- **Database**: SQLite (default), easily swappable with PostgreSQL
- **Other**: Django admin for easy moderation and content control

---

## 📦 Requirements

Make sure you have the following installed:

- Python 3.8+
- pip (Python package manager)
- Git
- Virtualenv (optional but recommended)

---

## 🚀 Setup Instructions

Clone the repository and run the server locally:

```bash
# Clone the repository
git clone https://github.com/kubadewerenda/CodeTalk-full-django-app.git
cd CodeTalk-full-django-app

# Create and activate a virtual environment (optional)
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create a superuser (admin access)
python manage.py createsuperuser

# Run the development server
python manage.py runserver

