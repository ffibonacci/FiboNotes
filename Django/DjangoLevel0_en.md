# Django-guide

## Create Django Project
```django-admin.py startproject project_name```
#### Create superuser for Admin panel
```python3 manage.py createsuperuser```
#### Make migrations
```
python3 manage.py makemigrations
python3 manage.py migrate
```
### Run server
```python3 manage.py runserver IP.ADRESS:PORT```

## Edit settings.py
#### Change Allowed Hosts
```ALLOWED_HOSTS = ['127.0.0.1', 'localhost']```

#### Login redirect url
```LOGIN_REDIRECT_URL = '/'```

#### Start app
```python3 manage.py startapp app_name```
