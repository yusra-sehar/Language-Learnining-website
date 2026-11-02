# Language Learning Website

A responsive language-learning website built with Django (back end) and
Bootstrap (front end). It was developed as a 3rd-semester course project to
practice full-stack web development: user authentication, database storage and
a responsive interface.

## Features
- User **sign-up and login**, with user data stored in the database (SQLite)
- Responsive layout built with Bootstrap, works on desktop and mobile screens
- Navigation, buttons and page layout for the language-learning interface

## Project Status
This is a learning project. Sign-up, login and database storage are fully
working. The language-learning content (lessons and exercises) is currently
implemented on the interface level only, and its back-end logic is not
implemented.

## Tech Stack
Python, Django (back end), HTML5, CSS3, Bootstrap (responsive front end), SQLite

## How to Run
1. Clone the repository
2. Install libraries: pip install -r requirements.txt
3. Run migrations: python manage.py migrate
4. Start the server: python manage.py runserver
5. Open http://127.0.0.1:8000/ in your browser

## What I Learned
- Building a Django project: models, views, URLs and templates
- Implementing user authentication with a database
- Creating responsive layouts with Bootstrap

## Future Improvements
- Add back-end logic for lessons, exercises and progress tracking
- Add quizzes and score storage per user
