# Django Project with PostgreSQL Database

This Django project template includes the necessary configuration in `settings.py` to use PostgreSQL as the database backend.

## `settings.py` Explanation

In the `settings.py` file of your Django project, you'll find the `DATABASES` dictionary where you can configure the database settings. Here's what each key-value pair means:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',  # Specifies the database engine (PostgreSQL in this case).
        'NAME': 'your_database_name',               # The name of your PostgreSQL database.
        'USER': 'your_database_user',               # The username used to connect to the PostgreSQL database.
        'PASSWORD': 'your_database_password',       # The password used to connect to the PostgreSQL database.
        'HOST': '',                                 # The host where the PostgreSQL database is running (localhost in this case).
        'PORT': '',                                 # The port on which the PostgreSQL database is listening (default is 5432).
    }
}
