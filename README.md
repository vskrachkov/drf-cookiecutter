# Django REST Framework and Postgres Cookiecutter Template

### Features
- `poetry` for managing project dependencies: https://python-poetry.org/
- `Django REST Framework` https://www.django-rest-framework.org/
- `environs` for managing environment variables: https://django-environ.readthedocs.io/en/latest/
- `dj-database-url` for configuring a database using a `DATABASE_URL` environment variable (https://github.com/jazzband/dj-database-url).
- `psycopg2-binary` for Postgres support.
- `django-storages` and `boto3` for utilising AWS S3 as Django Files Storage
- `django-dbbackup` - this Django application provides management commands to help backup and restore your project database and media files with various storages such as Amazon S3, DropBox or local file system (https://django-dbbackup.readthedocs.io/).
- `sentry_sdk` for integrations with https://sentry.io/
- `drf-spectacular` - flexible OpenAPI 3 schema generation for Django REST framework (https://drf-spectacular.readthedocs.io/).
- `django-cors-headers` - a Django App that adds Cross-Origin Resource Sharing (CORS) headers to responses. This allows in-browser requests to your Django application from other origins (https://github.com/adamchainz/django-cors-headers).
- `uvicorn` - ASGI server.
- `django-health-check` - https://github.com/revsys/django-health-check
- `python-json-logger` - output log data as json objects.
- `django-cid` - provides a correlation-id (also known as request id) is then available through the Django request/response cycle and may be automatically included in all log messages.
- drf_info_endpoint
- drf_spectacular_extensions
- Type hints support with `mypy`, `django-stubs` and `djangorestframework-stubs`.
- `pre-commit` for managing git pre-commit hooks: https://pre-commit.com
- `isort` for sorting python imports: https://pycqa.github.io/isort/
- `black` for python code formatting: https://black.readthedocs.io
- `bump2version` for bumping an application version with single command (https://pypi.org/project/bump2version/).


### How to use it
Go to the directory where you want to create your project and run:
```
pip3 install cookiecutter
python3 -m cookiecutter https://github.com/vskrachkov/drf-cookiecutter.git
```

Then just follow the instructions in the README.md file that is in the created project. 