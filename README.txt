                                       Progress till now

1. Install python 3.9, install pipenv to create virtual env
2. Used command pipenv shell to create "Pipfile"
3. Install Git-bash
4. use pipenv shell to activate environment
5. pip freeze to check which package is installed or not.
6. To install package in env use pipenv instead of pip
7. Install Django 3.1.4
8. To start django project use - "django-admin startproject ecom", where ecom is the name of the project.
9. Move to project using cd then run manage.py along with runserver - "python manage.py runserver"
10. "Makemigration" is used do the migration - what migration is - when we create schema uses classes that is conceptual
    Schema when we, migration then we create actual schema.
       command - "python manage.py makemigrations"
11. After make migrations we need to migrate the changes to reflect the changes
      command - "python manage.py migrate"
12. local/port/admin - open admin page
13. To create a super user use command - "python manage.py createsuperuser"