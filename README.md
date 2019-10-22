## django docs 2.2
tutorial from https://docs.djangoproject.com/en/2.2/

```sh
python -m django --version
django-admin startproject mysite

python manage.py startapp polls

python manage.py migrate

python manage.py makemigrations polls

# output query migration
python manage.py sqlmigrate polls 0001

# check
python manage.py check

python manage.py migrate

# django admin
python manage.py createsuperuser

```