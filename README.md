# drf-app-template
A template for using a common design in creating DRF apps

It generates apps of the formart:
```
app-name/
  application/
    __init__.py
    serializers.py
    views.py
  domain/
    __init__.py
    admin.py
    models.py
  migrations/
    __init__.py
  tests/
    __init__.py
    application/
      __init__.py
      test_endpoints.py
    domain/
      __init__.py
      test_domain.py
   apps.py

```
To use in project, `./manage.py startapp --template <url> <your-app-name>.
