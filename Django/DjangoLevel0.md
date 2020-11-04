## Создать Django-проект
```django-admin.py startproject имя_проекта```
#### Создать суперпользователя для панели администратора
```python3 manage.py createsuperuser```
#### Выполнить миграции
```
python3 manage.py makemigrations
python3 manage.py migrate
```
### Запустить сервер
```python3 manage.py runserver IP.АДРЕС:ПОРТ```

## Редактирование settings.py для запуска на локальном сервере 
#### Изменить допустимые хосты
```ALLOWED_HOSTS = ['127.0.0.1', 'localhost']```

#### url переадресации логина
```LOGIN_REDIRECT_URL = '/'```

#### Запуск Django-приложения
```python3 manage.py startapp имя_приложения```
