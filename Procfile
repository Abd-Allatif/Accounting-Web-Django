web: python manage.py makemigrations Accounting && python manage.py migrate && python manage.py collectstatic --no-input && gunicorn Accounting.wsgi.application