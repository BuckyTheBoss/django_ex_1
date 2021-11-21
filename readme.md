create virtualenv
py -m venv <name_of_env>

activate 
unix - source <name_of_env>/bin/activate
windows - <name_of_env>\scripts\activate

pip3 install django


django-admin startproject name_of_project

django-admin startapp name_of_app

add name_of_app to INSTALLED_APPS in settings.py

add urls.py to name_of_app
    from django.urls import path
    urlpatterns = [    
    ]

Create a view in views.py
create a path in urls.py using that view
profit???
