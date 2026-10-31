# Development Log — Kumbh Mela Management System

This document records the actual development and deployment work completed for the Kumbh Mela Management System.

## Project Overview

The Kumbh Mela Management System is a Flask-based web application designed to manage registrations and related information for Kumbh Mela operations.

## Technology Stack

- **Language:** Python 3.12
- **Backend:** Flask 3.1.3
- **Frontend:** HTML and CSS
- **Database:** SQLite
- **Data Handling:** CSV
- **Version Control:** Git and GitHub
- **Hosting:** PythonAnywhere

## Development and Deployment Timeline

### 1. Project Repository Setup

- Created the `kumbhmela` GitHub repository.
- Uploaded the Flask application source code.
- Added the project folders: `data`, `static`, and `templates`.
- Added the `.gitignore` file.

### 2. PythonAnywhere Setup

- Created a PythonAnywhere web application using Python 3.12.
- Cloned the GitHub repository into the PythonAnywhere account.
- Set up a Python virtual environment named `kumbhmela-venv`.
- Installed Flask and its dependencies.

### 3. Database Initialization

- Identified the database initialization function in `app.py`.
- Initialized the SQLite database on the hosting server.
- Generated `kumbhmela.db` using the application's `init_db()` function.

Command used:

```bash
python -c 'from app import init_db; init_db(); print("Database initialized successfully")'
