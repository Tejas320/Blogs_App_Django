# Blog App using Django Framework

## Tools Used:
### Python, Django, HTML, CSS, Bootstrap

A full-featured blogging platform built with the **Django framework**. This app allows users to create, update, delete, and read blog posts. It supports user authentication, rich text formatting, and more — making it a great starting point for a personal blog, portfolio, or content-driven website.

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Project Structure](#project-structure)
4. [Snapshots](#snapshots)

## Features

- User authentication (Sign up, Login, Logout)
- Create, Read, Update, Delete (CRUD) blog posts
- Responsive front-end using Bootstrap
- Admin dashboard to manage content
- SEO-friendly URLs and meta tags

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Tejas320/Blogs_App_Django.git
cd blog_app
```
### 2. Set up a virtual environment

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install requirements

```bash
pip install -r requirements.txt
```
### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Create superuser

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

### Visit http://127.0.0.1:8000/blogs/ in your browser to see the app.

## Project Structure
```bash
blog_app/
│
├── blog_app/                 # App containing blog logic
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
    ├── urls.py
    ├── wsgi.py
│   └── __pycache__/
│
├── blogs/                
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── tests.py
    ├── urls.py
│   └── views.py
│
├── static/               # Static files (CSS, JS)
├── media/                # Uploaded images, media files
├── templates/            # Base templates
├── manage.py
├── requirements.txt
```

## Snapshots
