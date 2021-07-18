# calorie-calculator-python-code

#To create from the scratch

django-admin startproject CalorieClac
cd  CalorieClac
django-admin startapp Fityfeed


#To make the superuser

py manage.py makemigrations
py manage.py migrate
py manage.py createsuperuser


#To run the source code 

py manage.py migrate
py manage.py runserver