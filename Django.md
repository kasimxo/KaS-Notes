# Django

## Create basic Django project

First, you will need to have python installed
We are going to use a venv in order to avoid installing packages in the global environment

Create a venv
> python3 -m venv venv

Activate said venv

| Windows | Linux |
| -- | -- |
| .\venv\Scripts\Activate.ps1 | source ./venv/bin/activate | 

Install Django in the venv
> pip install django

Create the Django project 
> django-admin startproject config .

Execute the project to verify it works
> python manage.py runserver

Generate migrations
> python manage.py makemigrations

Commit migrations
> python manage.py migrate

Show migrations
> python manage.py showmigrations

Generate archivo requirements.txt
> pip freeze > requirements.txt

Install dependencies from requirements.txt
> pip install -r requirements.txt

