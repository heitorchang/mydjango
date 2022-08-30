# My Django

Initial project with CustomUser.

Add a file `mydjango/mysecrets.py` with:

```
SECRET_KEY = "...some random string..."
ALLOWED_HOSTS = ['localhost', 'mydomain.com']
CSRF_TRUSTED_ORIGINS = ['https://mydomain.com']
```

Set `DEBUG = False` when deploying to production.
