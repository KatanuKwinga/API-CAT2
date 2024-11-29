# API-CAT2
Created a virtual environment;

python -m venv myvenv.

Installed django amd rest_framework
pip install django 
pip install django djangorestframework
# Question One
Created a new project 'Question One'
django-admin startproject QuestionOne

Inside The project/models.py create the models customer and order with the fields for each
Customer (name, email, phone)
Order (customer, product, quanity, date_ordered)
Created migrations
# Question Two
Created a new project 'QuestionTwo' and inside it a new app 'products'

Within products created the product model with name, description and price attributes

Ran migrations
python manage.py makemigrations
python manage.py migrate

Created a serializer

Built views

Set up URLs

Run the server
python manage.py runserver

Created a requests file
