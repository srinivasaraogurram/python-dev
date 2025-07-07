python -m venv djangoenv
source djangoenv/bin/activate
deactivate

pip install django
django-admin startproject my_tennis_club

python manage.py startapp members

djangoenv