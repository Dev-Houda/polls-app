🗳️ Polls Application

A full-stack web application built with Django, allowing users to create polls, vote, and view results in real time.

This project demonstrates clean architecture, use of Django’s ORM, and a fully functional admin panel for managing content.

🚀 Features

Poll Management – Create, edit, and delete polls via the Django Admin.

Voting System – Users can cast votes on poll choices.

Results Display – See live results updated after voting.

Admin Dashboard – Secure backend to manage polls and choices.

Responsive UI – Clean, minimal, and works across devices.


⚙️ Installation & Setup

Clone the repository and set up the project locally:

git clone https://github.com/Dev-Houda/polls-app.git
cd polls-app

1. Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

2. Install Dependencies
pip install -r requirements.txt

3. Run Migrations
python manage.py migrate

4. Create Superuser
python manage.py createsuperuser

5. Start Development Server
python manage.py runserver


Visit:

http://127.0.0.1:8000/polls/ → User-facing polls

http://127.0.0.1:8000/admin/ → Admin dashboard

🛠️ Tech Stack

Backend: Django, Python

Database: SQLite (default) → easily switchable to PostgreSQL/MySQL

Frontend: Django Templates, Bootstrap 

Authentication & Security: Django Auth, CSRF protection

📂 Project Structure
polls-app/
│── polls/           # Main polls app (models, views, urls, templates)
│── mysite/          # Project configuration
│── db.sqlite3       # Default database
│── manage.py        # Django project manager
│── requirements.txt # Dependencies