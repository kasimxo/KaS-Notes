# Django

## Create basic Django project

First, you will need to have python installed
We are going to use a venv in order to avoid installing packages in the global environment

Create a venv
> python3 -m venv venv

Activate said venv
> .\venv\Scripts\Activate.ps1

Install Django in the venv
> pip install django

Create the Django project 
> django-admin startproject config .

Execute the project to verify it works
> python manage.py runserver
