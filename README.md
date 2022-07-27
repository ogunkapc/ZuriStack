# ZuriStack

A StackOverflow clone

- # Guide

<hr>

    - Create a virtual environment on your system
    - activate it
    - install packages from requirements.txt
    - add django_extensions to installed apps array in settings.py file
    - generate secret key with python manage.py generate_secret_key
    - create .env file and add secret key as well as debug to it
    - add python decouple and make insecure secret key default
    - add * to ALLOWED_HOSTS array to allow this project run on any host/machine
    - add template and static to respective DIRS in settings.py
