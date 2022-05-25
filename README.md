# LAB - Class 28
Project: Django CRUD \
Author: Benjamin Carter \ 
Links and Resources \
back-end server url (when applicable)\
front-end application (when applicable)\
___
## Setup
```bash
py -m venv .venv ..venv\Scripts\activate
pip install django
django-admin startproject snacks_project .
python manage.py migrate
python manage.py runserver
python manage.py startapp snacks
python manage.py makemigrations app_name
python manage.py migrate
python manage.py createsuperuser
Username: ________
password: ________
python manage.py runserver
```
___

## Tests
How do you run tests? \
`python manage.py test`

Any tests of note?

Describe any tests that you did not complete, skipped, etc