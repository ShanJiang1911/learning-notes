### [Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)
* Configuration setting approaches
  * settings_local.py: Pros & Cons
  * Separate settings file for each environment: make a setting package
  * Environment variables: need to handle KeyError exceptions;
  * 12 Factors: created by Heroku, collection consists of 12 parts
  * django-environ
```
Django Settings: Best practices
Keep settings in environment variables.
Write default values for production configuration (excluding secret keys and tokens).
Don’t hardcode sensitive settings, and don’t put them in VCS.
Split settings into groups: Django, third-party, project.
Follow naming conventions for custom (project) settings.
```


### [SSH Tutorial](https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work)
* SSH: Secure Shell. remote administration protocol that allows users to control and modify their remote servers over the Internet
* The SSH command consists of 3 distinct parts: ```ssh {user}@{host}```
* Symmetric Encryption: use security for both decryption and encryption by both the clien and hose
* Asymmetric Encryption: use public key and private key to encryption and decryption.
* Authenticating the User: user name and password

### [White Noise](http://whitenoise.evans.io/en/stable/)

### [IaaS](https://en.wikipedia.org/wiki/Infrastructure_as_a_service)

### [PaaS](https://en.wikipedia.org/wiki/Platform_as_a_service)

### [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)

[<--Back](README.md)