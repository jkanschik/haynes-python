
Activate environment on Windows with Git Bash
    source .venv/Scripts/activate

# Run server (development mode)
* `py manage.py runserver` will run the application
* `py manage.py tailwind start` will watch the templates and regenerate css if necessary.

# Installation process

* `django-admin startproject haynes .` to initialise an empty django project
* Configured `settings.py` to use configuration from file `env`
* Followed installation on https://django-tailwind.readthedocs.io/en/latest/installation.html