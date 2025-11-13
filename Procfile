release: python manage.py migrate && python manage.py createsuperuser --noinput || true
web: gunicorn library_project.wsgi