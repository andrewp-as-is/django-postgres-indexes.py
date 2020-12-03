<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-postgres-indexes.svg?maxAge=3600)](https://pypi.org/project/django-postgres-indexes/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-postgres-indexes.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-postgres-indexes.py/actions)

### Installation
```bash
$ [sudo] pip install django-postgres-indexes
```

#### Examples
variant 1:

`settings.py`
```python
INSTALLED_APPS+= ["django_loadsql"]
```

```bash
$ find . -name '*.sql' | xargs python manage.py loadsql
```


variant 2:
```bash
export DJANGO_SETTINGS_MODULE=settings.dev
find . -name '*.sql' | xargs python -m django_loadsql
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
