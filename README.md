# Product Management System — Django

A web-based **Product Management System** built with Django that demonstrates CRUD operations, user authentication, database management, form validation, and responsive web development.

The project provides a simple interface for users to register, log in, and manage product records through Create, Read, Update, and Delete operations.

## Features

- User Registration and Login
- User Logout functionality
- Create new products
- View product records
- Update existing products
- Delete products
- Product detail view
- Form validation and error handling
- Responsive UI using Bootstrap
- Django Admin Panel
- Database integration with SQLite/PostgreSQL
- Health check endpoint for basic application monitoring

## Application Overview

The application provides an easy-to-use interface for managing product information.

### CRUD Operations

- **Create** — Add new products through a web form.
- **Read** — View all available products and individual product details.
- **Update** — Edit existing product information.
- **Delete** — Remove unwanted product records.

## User Authentication

The application includes a basic authentication system that allows users to:

- Register a new account
- Log in using their credentials
- Access product management features
- Log out securely

## User Interface

The application uses **Bootstrap** to provide a clean, responsive, and user-friendly interface.

The interface includes:

- Navigation bar
- Login and registration pages
- Product listing
- Product creation form
- Product update form
- Product detail page
- Delete functionality
- Responsive layouts

## Technology Stack

### Backend
- **Python**
- **Django**

### Frontend
- **HTML**
- **CSS**
- **Bootstrap**
- **Font Awesome**

### Database
- **SQLite** for development
- **PostgreSQL** support

### Deployment & Server
- **Gunicorn**
- **WhiteNoise**
- **Render**

## Project Structure

```text
django-product-management/
│
├── manage.py
├── requirements.txt
├── render.yaml
├── Procfile
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── admin.py
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   └── products/
│
└── static/
````

## Getting Started

### Prerequisites

Make sure the following are installed:

* Python 3.x
* pip
* Git
* SQLite or PostgreSQL

### Installation

#### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <project-folder>
```

#### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment.

**Linux/macOS:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

#### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

#### 4. Apply Database Migrations

```bash
python manage.py migrate
```

#### 5. Create a Superuser

To access the Django administration panel:

```bash
python manage.py createsuperuser
```

Follow the instructions provided in the terminal.

#### 6. Start the Development Server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## Usage

After starting the application:

1. Register a new user account.
2. Log in using your credentials.
3. Open the product management section.
4. Create a new product.
5. View the available products.
6. Update product information when required.
7. Delete products when they are no longer needed.
8. Use the Django Admin Panel for administrative management.

## Database

The project uses Django's ORM for database interaction.

Django models represent product data, while migrations are used to create and maintain the database structure.

For local development, SQLite can be used. PostgreSQL can also be configured through Django's database settings.

## Deployment

The project can be deployed using **Render** with **Gunicorn** as the application server.

Deployment configuration includes:

* `render.yaml` — Render deployment configuration
* `Procfile` — Application start command
* `Gunicorn` — Production WSGI server
* `WhiteNoise` — Static file serving
* Environment variables — Application configuration

### Environment Variables

For deployment, configure environment variables such as:

```text
SECRET_KEY
DEBUG
ALLOWED_HOSTS
DATABASE_URL
```

Sensitive configuration values should not be committed directly to the repository.

## Key Learning Outcomes

Through this project, I worked with:

* Django project and application structure
* Django URL routing
* Django Models and ORM
* CRUD operations
* User authentication
* HTML templates
* Bootstrap-based UI development
* Form handling and validation
* Database migrations
* SQLite/PostgreSQL integration
* Django Admin
* Basic deployment concepts
* Git and GitHub workflow

## Project Highlights

* Developed a complete **CRUD-based web application** using Django.
* Implemented database operations using **Django ORM**.
* Added user registration and login functionality.
* Built a responsive web interface using **Bootstrap**.
* Implemented form validation and error handling.
* Integrated database migrations for managing application data.
* Configured the application for deployment using **Gunicorn and Render**.

## Author

### Mohammad Yasin Naeemuddin Siddique

**B.Tech Computer Science & Engineering**
**GH Raisoni College of Engineering, Nagpur**

* **GitHub:** https://github.com/MYSiddique2005
* **LinkedIn:** `https://www.linkedin.com/in/mohammad-yasin-siddique-085b1b316/

## License

This project is intended for **educational and project showcase purposes**.
