release: python manage.py migrate
web: gunicorn blog_project.wsgi:application --log-file -
