![](https://shields.io/github/v/release/louisjgrange/django-admin?display_name=tag) [![](https://img.shields.io/badge/django-4.1.7-blue)](https://www.djangoproject.com/) ![](https://shields.io/github/repo-size/louisjgrange/django-admin) ![](https://shields.io/github/issues-raw/louisjgrange/django-admin) ![](https://shields.io/github/last-commit/louisjgrange/django-admin)

# Django Admin Magnify
A lightweight package to make your django admin website look more modern and secure.
## Features
- Updated UI for every admin page
- Two-factor authentification (2FA)
- More features coming...
## Installation
First, install this package normally with pip
```console
pip3 install django-admin-magnify
```
Then, add the new django admin interface to your application list in your-project/settings.py
```python
INSTALLED_APPS = [
  'magnify',
  ...
]
```
You can now run your Django server with
```console
python3 manage.py runserver
```
## Configuration
A few settings are available in your project settings.py file
```python
MAGNIFY_2FA = False # In the django admin
```
## Customization
Currently, no options are available for customization, but I'm working on it !
