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
13. To create a super user use command - "python manage.py createsuperuser".
14. cross origin requests in django
    14.1 install using pipenv command - pipenv install django-cors-headers
    14.2 open settings.py and do following changes
         14.2.1 add line to INSTALLED_APPS=[]
         14.2.2 add line to MIDDLEWARE = []
         14.2.3 set CORS_ALLOW_ALL_ORIGINS to True
                 link of docs - https://pypi.org/project/django-cors-headers/
15. Install Django rest framework
     15.1 pipenv install djangorestframework and open settings.py
     15.2 add rest_framework and rest_framework.authtoken to installed apps.
     15.3 add rest_framework dictionary in file from docs
     15.4 open api_guide from documentation link and open Authentication
     15.5 and copy default_authentication_class in rest_frame_work dict
     15.6 add custom line in default_dict to enable token based auth.
     15.7 open urls.py and do changes

16. Add media files
    16.1 create folder named as media
    16.2 add media_url and media_root in setting file
    16.3 import setting and add url_pattern

17 Create new app as api
   17.1 create new django api by using django-admin startapp "api", api - name, keep the name in lowercase
   17.2 create subapps like category, user, product, payment, order
   17.3 as these are also apps we need to add it into settings file 'installed_apps'
   17.4 add url of api
   17.5 inside api create views.py and write it from scratch
   17.6 create home() in views and add it in url

18 Setting up category model and admin
   18.1 

