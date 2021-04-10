# First-full-stack

## Tree

```bash 
├── README.md
└── missweb
    ├── UserView
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── __init__.cpython-38.pyc
    │   │   ├── urls.cpython-38.pyc
    │   │   └── views.cpython-38.pyc
    │   ├── admin.py
    │   ├── apps.py
    │   ├── migrations
    │   │   └── __init__.py
    │   ├── models.py
    │   ├── tests.py
    │   ├── urls.py
    │   └── views.py
    ├── db.sqlite3
    ├── manage.py
    └── missweb
        ├── __init__.py
        ├── __pycache__
        │   ├── __init__.cpython-38.pyc
        │   ├── settings.cpython-38.pyc
        │   ├── urls.cpython-38.pyc
        │   └── wsgi.cpython-38.pyc
        ├── asgi.py
        ├── settings.py
        ├── urls.py
        └── wsgi.py
```

## Instruction 
### Start

1. go to the working dir
```
(base) ➜  First-full-stack ls
17site    README.md missweb
```
2. open the virtual env 
```
(base) ➜  First-full-stack source 17site/bin/activate
(17site) (base) ➜  First-full-stack 
```
3. go to first **missweb**
```
(17site) (base) ➜  missweb ls
UserView   db.sqlite3 manage.py  missweb
```
4. run the app 
```
(17site) (base) ➜  missweb python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
April 10, 2021 - 16:41:14
Django version 3.2, using settings 'missweb.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

### Close

1. deactivate

## Useful links:

- Deployed Django on [Alicloud](https://www.alibabacloud.com/blog/deploy-django-application-on-alibaba-cloud_595833)