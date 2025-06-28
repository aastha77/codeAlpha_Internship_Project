# 🍽️ Django Recipe API

A simple Django REST Framework-based API to manage recipes — built for learning and backend practice.

## 📌 Features

- ✅ Add, view, update, and delete recipes
- ✅ Stores title, description, ingredients
- ✅ Automatically stores creation time (`created_at`)
- ✅ Browsable API using Django REST Framework
- ✅ Clean project structure

## 📂 Project Structure

recipe_project/
├── recipes/ # App containing models, views, serializers, urls
├── recipe_project/ # Project settings
├── db.sqlite3 # SQLite database (auto-created)
├── manage.py # Django CLI
├── README.md # Project documentation


## ⚙️ Tech Stack

- **Backend**: Django 5.2.3, Django REST Framework
- **Database**: SQLite (default)

## 🚀 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/aastha77/recipe_project.git
   cd recipe_project

2.**Create and activate virtual environment**
python -m venv env
env\Scripts\activate  # On Windows

3.**Install dependencies**
pip install django djangorestframework

4.**Run migrations**
python manage.py makemigrations
python manage.py migrate

5.**Run the server**
python manage.py runserver

6.**Visit the API**
Browse: http://127.0.0.1:8000/api/recipes/


API Endpoints
Method	Endpoint	         Description
GET	    /api/recipes/	     List all recipes
POST	/api/recipes/	     Create a new recipe
PUT	    /api/recipes/<id>/	 Update a recipe
DELETE	/api/recipes/<id>/	 Delete a recipe

Author
Aastha Pandey
Aspiring software developer | Python & Django enthusiast
🔗 GitHub
🔗 LinkedIn

