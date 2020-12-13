# DJACT-API A starter/demo Django api

Implements [REST framework JWT](https://jpadilla.github.io/django-rest-framework-jwt/)
based on this article: [Django & React: JWT Authentication](https://medium.com/@dakota.lillie/django-react-jwt-authentication-5015ee00ef9a)

## Getting Started
### Clone the repo & cd to its root folder:
```
git clone git@github.com:chrisfield/djact-api.git
cd djact-api
```

### create & activate a virtual env:
```
python3 -m venv env
source env/bin/activate
```

### Add models to database schema
```
python manage.py migrate
```

### Create a superuser
```
python manage.py createsuperuser
```

### Run the server
```
python manage.py runserver
```

### Run the web frontend webserver
A React implementation of a webserver using this api can be found [here](https://github.com/chrisfield/djact-web).