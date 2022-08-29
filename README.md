# django-celery-redis
In this repo I will integrate Celery and Redis with Django.


## Important Terminal Commands

### Create a Django Project
```
django-admin startproject django_celery .
```
### Create a Django App
```
django-admin startapp feedback
```

### Make Migrations
```
python manage.py runserver
```

### Start celery worker
```
python -m celery -A django_celery worker -l info
```

### Start redis server
```
redis-server
```
