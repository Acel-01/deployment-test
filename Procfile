release: python manage.py makemigrations base
release: python manage.py migrate

web: gunicorn todo_list.wsgi
