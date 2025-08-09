# E-commerce Backend

This project is a basic e-commerce backend built with Django and Django REST Framework. It defines `Product` and `Order` models and exposes RESTful endpoints to manage them.

## Setup Instructions

1. Install dependencies:

```bash
pip install django djangorestframework
```

2. Apply migrations:

```bash
python manage.py migrate
```

3. Run the development server:

```bash
python manage.py runserver
```

4. Access the API at `http://127.0.0.1:8000/api/`.

This skeleton includes a simple SQLite database configuration. Customize `ecommerce_backend/settings.py` for other databases.
