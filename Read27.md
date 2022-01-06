## [Using Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)
* Django web applications access and manage data through models
* Think about what data we need to store and the relationships between the different objects before building models
* Models are usually defined in models.py
* from django.db import models
* A model can have an arbitrary number of any type fields
  * common field arguments:  help_text, verbose_name, default, null, blank, choices, primary_key. etc
  * common field types: CharField, TextField, IntegerField, DateField, EmailField, FileField, AutoField, ForeignKey, manyToManyField. etc
* Class Meta can declare model-level metadata
  * control the default order 
* Common methods: __str__(self), get_absolute_url(self)
* Creating and modifying records
* filter() method can filter returned QuerySet to match a specified text or numeric field
* Book model, BookInstance model, Author model
* re-run database migrations to add changes: 
  * python manage.py makemigrations
  * python manage.py migrate


## [Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
* Registering models: 
  * from django.contrib import admin
* from .models import Book
  * admin.site.register(Book)
* Create a superuser:
  * python manage.py createsuperuser
* "python manage.py runserver" and open the admin page


## [Beginner’s Guide to Django - Part 1](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html)

## [Beginner’s Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)

[<--Back](README.md)