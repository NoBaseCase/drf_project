## Clone the application and navigate into the main folder directory

`git clone https://github.com/NoBaseCase/drf_project.git`

## Create virutal environment

`python -m venv env`

## Activate the virtual environment

`source env/scipts/activate`

## Install package dependancies

`pip install -r requirements.txt`

## create database migrations

`python manage.py makemigrations`

## apply created migrations

`python manage.py migrate`

## create admin user

`python manage.py createsuperuser`

## runserver locally

`python manage.py runserver`
