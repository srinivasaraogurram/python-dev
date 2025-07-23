python -m venv djangoenv
source djangoenv/bin/activate
deactivate

pip install django
django-admin startproject my_tennis_club

python manage.py startapp members

djangoenv

python manage.py migrate

python manage.py makemigrations members
python manage.py migrate
python manage.py sqlmigrate members 0001