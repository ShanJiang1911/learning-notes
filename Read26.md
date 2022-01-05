### [Getting started with Django](https://www.djangoproject.com/start/)
* Object-relational mapper
  * Model: definitive source of information about your data. It contains the essential fields and behaviors of the data you’re storing. Generally, each model maps to a single database table
  * Each model is a Python class that subclasses django.db.models.Model
  * " from django.db import models "
* URLs and views
  * Django lets you design URLs however you want, with no framework limitations 
* Templates
* Forms
```
  from django import forms

class BandContactForm(forms.Form):
    subject = forms.CharField(max_length=100)
    message = forms.CharField()
    sender = forms.EmailField()
    cc_myself = forms.BooleanField(required=False)
```
* Authentication
* Admin
```
from django.contrib import admin
from myapp.models import Author

class AuthorAdmin(admin.ModelAdmin):
    pass
admin.site.register(Author, AuthorAdmin)
```
* Internationalization
  * Django can translate text into different languages 
* Security 
### [How Django Works Behind the](https://wsvincent.com/how-django-works-behind-the-scenes/)
* Django Software Foundation(DSF)
* Django code is lead by a core team of volunteers, two paid Django Fellows, and a larger group of contributors
### [What is Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
### [First Django App - Part 1](https://docs.djangoproject.com/en/3.0/intro/tutorial01/)
### [First Django App - Part 2](https://docs.djangoproject.com/en/3.0/intro/tutorial02/)

[<--Back](README.md)