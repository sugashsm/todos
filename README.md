# Django Todo Application

A simple Todo application built with Django featuring user authentication and SQL database integration.

## Features
- User Authentication (Register, Login, Logout)
- Create, Read, Update, and Delete Todos
- Mark Todos as Complete/Incomplete
- User-specific Todos

## Setup Instructions
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run migrations:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

3. Create superuser (optional):
   ```
   python manage.py createsuperuser
   ```

4. Run the development server:
   ```
   python manage.py runserver
   ```

5. Access the application at http://127.0.0.1:8000/
