# University Registration System

A web-based student registration application built with Flask and SQLite. Users can submit student details through a form, which are stored in a local database.

## Overview
The app runs a lightweight Flask server backed by a SQLite database. On startup, it automatically creates the database and a `students` table if they don't already exist, so the project runs out of the box with no manual database setup.

## Features
- **Homepage** — landing page for the application
- **Add Student** — a form to submit a student's name and address, which is saved to the database
- **Automatic database initialization** — the database and schema are created automatically on first run

## Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML templates (Jinja2), static CSS

## Getting Started

### Prerequisites
- Python 3
- pip

### Installation
```bash
git clone https://github.com/MohammadSameerKhan/university-registration-system.git
cd university-registration-system
pip install -r requirements.txt
```

### Running the app
```bash
python app.py
```
The app will be available at `http://127.0.0.1:5000/`.

## Project Structure

university-registration-system/
├── app.py # Main Flask application and routes
├── database/ # SQLite database (auto-created on first run)
├── templates/ # HTML templates (Jinja2)
├── static/ # CSS and static assets
└── requirements.txt # Python dependencies


## Skills Demonstrated
- Building and routing a Flask web application
- Integrating SQLite for persistent data storage
- Handling form submissions (GET/POST) and redirects
- Structuring a small full-stack web project (backend, templates, static assets)
