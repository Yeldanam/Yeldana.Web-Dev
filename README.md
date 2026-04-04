# Lab 10: Building API Views

## Run
```bash
python -m venv venv
venv\Scripts\activate
pip install django djangorestframework
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Active level
`api/views/__init__.py` imports from `generics.py`

## Endpoints
- GET/POST `/api/products/`
- GET/PUT/DELETE `/api/products/<id>/`
- GET/POST `/api/categories/`
- GET/PUT/DELETE `/api/categories/<id>/`
- GET `/api/categories/<id>/products/`
