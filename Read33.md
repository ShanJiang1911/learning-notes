### [JSON Web Tokens](https://jwt.io/introduction/)
* JSON Web Token (JWT): a compact and self-contained way for securely transmitting information between parties as a JSON object
* When use JWT:
  * Authorization
  * Information Exchange
* JSON Web Token structure: ```Header.Payload.Signature```
* Click [Here](https://jwt.io/#debugger-io) to practice decode, verify, and generate JWTs

### [DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
* [How to Implement Token Authentication using DRF](https://simpleisbetterthancomplex.com/tutorial/2018/11/22/how-to-implement-token-authentication-using-django-rest-framework.html)
* Installation & Setup process inside the article
* Example Code & Usage

### [Django Runserver Is Not Your Production Server](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
* django runserver is built for development convenience, not for production setup
* Nginx is an example for a good web server
```
If you want to run Django in production, be sure to use a production-ready web server like Nginx, and let your app be handled by a WSGI application server like Gunicorn.
If you plan on running on Heroku, a web server is provided implicitly. You don’t have to take care of it. You just need to specify a command to run your application server (again, Gunicorn is fine) in the Procfile
```


### [JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

### [Gunicorn](https://gunicorn.org/)
### [Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)

[<--Back](README.md)