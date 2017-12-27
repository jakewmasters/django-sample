# django-sample
A basic Django app.

## Prerequisites
I developed this application on a Windows machine, so some of the commands will vary depending on your OS.  

## Setup
First, I would advise using PyCharm for an IDE as it makes Django development fairly simple.  

To setup a development environment:  
1. Clone this repository.  
2. Create and activate a virtualenv*.  
3. In the PyCharm terminal, run `$ pip install -r requirements.txt`.  
4. You're ready to go!  

*For further reference on project setup, see https://djangoforbeginners.com/initial-setup/

In addition to setting up a development environment, I also ran the following commands:  
1. `$ django-admin.py startproject sample_project . `  
 - This command created a new Django project called `sample_project`.  
2. `$ python manage.py startapp sample_app`  
 - This command created a new Django app called `sample_app`.  
3. `$ python manage.py runserver`  
 - This command starts a development server, with details printed out in the Terminal.  

## Components
*This section under minor construction*  
This sample Django application demonstrates several key features of Django:  
- ORM  
  - Django ships with its own built-in Object-Relational Mapper (ORM), which is interfaced with in `models.py`.  
  - For more information on Django Models, see https://docs.djangoproject.com/en/1.11/topics/db/models/  
- Django Views  
  - In order to make use of the data described in Django Models, Django ships with its own Views interface in `views.py`.  
  - For more information on Django Views, see https://docs.djangoproject.com/en/1.11/topics/http/views/  
  - For some extremely detailed information on different kinds of views, see https://ccbv.co.uk/  
  - Django views allow for the creation of Querysets, which are collections of database objects.  
  - For more information on making queries in Django, see https://docs.djangoproject.com/en/1.11/topics/db/queries/  
  - For more information about Querysets, see https://docs.djangoproject.com/en/1.11/ref/models/querysets/  
- Django templating language  
  - In order to display data gathered in Querysets, `Context` objects can be created in `views.py`.  
  - The contents of `Context` objects can be displayed in HTML using the Django templating language.  
  - For more information on the Django templating language, see https://docs.djangoproject.com/en/2.0/ref/templates/api/   

## References  
Here are some resources I found to be extremely helpful:  
https://docs.djangoproject.com/en/1.11/  
https://djangoforbeginners.com/  
https://ccbv.co.uk/  
https://simpleisbetterthancomplex.com/  
