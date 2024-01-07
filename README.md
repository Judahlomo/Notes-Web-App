# Notes App
The Notes Website is a Flask-based web application that allows users to create, manage, and store notes securely. It is built using Flask, Python, HTML, and JavaScript, integrating Flask-SQLAlchemy and flask-login for user authentication and data management.

# Features
User registration and authentication.
Ability to add, view, and delete notes.
Responsive interface using Bootstrap for a better user experience.

# Files and Folders
__init__.py: Initializes the Flask application, configures the database, and sets up necessary app context.

auth.py: Manages user authentication, including login, logout, and user registration.
models.py: Defines database models for users and notes using Flask-SQLAlchemy.

views.py: Includes route handlers for rendering templates, handling notes, and managing the home page.

base.html: Defines the base layout template for the website with navigation and flash messages.

home.html: Renders the home page where users can view, add, and delete notes.

login.html: Provides the login form for users to authenticate themselves.

sign-up.html: Allows new users to register by providing necessary details.

# Requirements
Python
Flask
Flask-SQLAlchemy
flask-login
