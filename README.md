**Current updates to 'django.contrib.staticfiles' in settings.py**
- MIDDLEWARE = [
    'allauth.account.middleware.AccountMiddleware',  # Add this line
]
- python manage.py migrate