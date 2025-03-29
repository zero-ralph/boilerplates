### Django Directory Structure 

This is a sample django directory structure which I prefer to use in every project.


#### Feature Creation
Kindly refer to django's documentation on how to create a feature

or

> $ cd path/to/your/project

> $ pyenv activete (your virtual env)

> $ python manage.py startapp (your app)

#### Tree Structure

```
├── config                       - This is where your settings 
│   ├── asgi.py
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── features                     - This is the director structure of the feature application
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── repository                - This is optional just in case you prefer working with service repository pattern
│   │   └── __init__.py
│   ├── service                   - This is optional just in case you prefer working with service repository pattern
│   │   └── __init__.py
│   ├── tests.py
│   └── views.py                  - This is where your views / controller goes
├── manage.py
└── README.md
```