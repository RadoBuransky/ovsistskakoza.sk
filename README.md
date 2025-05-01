# ovsistskakoza.sk

## Development

1. https://docs.djangoproject.com/en/5.2/howto/windows/
   1. `py -m venv venv`
   1. `py -m pip install Django`
   1. `py -m pip install "colorama >= 0.4.6"`
   1. `pip freeze > requirements.txt`
1. https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html
1. https://medium.com/@nomannayeem/complete-ci-cd-with-github-actions-and-aws-for-python-developers-a-step-by-step-guide-92807f6167ee
   1. `py manage.py startapp core`
1. https://medium.com/django-unleashed/django-project-structure-a-comprehensive-guide-4b2ddbf2b6b8
1. https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Django/Deployment
   1. `py manage.py check --deploy`
   1. `SECRET_KEY`
   1. `DEBUG`
   1. `ALLOWED_HOSTS`

## Run Locally

Two options:
1. Python
   1. `venv\Scripts\activate.bat`
   1. `py manage.py runserver` 
1. Docker
   1. `docker-compose build`
   1. `docker-compose up`
