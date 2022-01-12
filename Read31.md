### [Beginner’s Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)
* Docker: Linux containers which are a type of virtualization
* Image: a snapshot in time of what a project contains
* Container: a running instance of the image
* Dockerfile: content of the container
* docker-compose.yml: how the container set up
* Image Layers: every image is made up of one or more image layers
* Dockerfile commands: RUN, COPY, ADD
```
# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /code

# Install dependencies
COPY Pipfile Pipfile.lock /code/
RUN pip install pipenv && pipenv install --system

# Copy project
COPY . /code/
```

### [Django for APIs - Library Website](https://djangoforapis.com/library-website-and-api/)
```
__init__.py is a Python way to treat a directory as a package; it is empty
asgi.py stands for Asynchronous Server Gateway Interface and is a new option in Django 3.0+
settings.py contains all the configuration for our project
urls.py controls the top-level URL routes
wsgi.py stands for Web Server Gateway Interface and helps Django serve the eventual web pages
manage.py executes various Django commands such as running the local web server or creating a new app.
```
```
admin.py is a configuration file for the built-in Django Admin app
apps.py is a configuration file for the app itself
the migrations/ directory stores migrations files for database changes
models.py is where we define our database models
tests.py is for our app-specific tests
views.py is where we handle the request/response logic for our web app
```
* Django REST Framework: 
```
(library) $ pipenv install djangorestframework~=3.11.0
```
  * add 'rest_framework' to installed_apps in settings.py
* Serializer: translates data into a format that is easy to consume over the internet, typically JSON, and is displayed at an API endpoint
* cURL
* Browsable API

### [Beginner’s Guide to Django REST Framework](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)



[<--Back](README.md)