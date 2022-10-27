
# RestAPI using Django Framework

A simple project that use Django framework to build a CRUD RestAPI

## How to run

Install the dependencies with command `make install-dependencies`
Run the server with command `make run` 
Acess the URL below to use the CRUD aplication

http://127.0.0.1:8000/core/

## Some Django commands example:

Start a project using Django framework: `django-admin startproject app .`

Create a super user for the api: `python manage.py createsuperuser`

Start a app structure with Django: `python manage.py startapp core`

Start the migrations structure: `python manage.py makemigrations`

Update the migations: `python manage.py migrate`

Run the Django server: `python manage.py runserver`