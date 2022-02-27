# Django-starter

This boiler-plate is made for starting a project with Django 4 and tailwindcss 3 with postgresql database.

author of this repo : Valentin FIGUEIREDO

## Features

- Production-ready


## Packages installed

- django
- [pillow](https://pypi.org/project/Pillow/)
- [psycopg2](https://pypi.org/project/psycopg2/)
- [python-environ](https://pypi.org/project/python-environ/)
- [django-tailwind](https://pypi.org/project/django-tailwind/)

## Installation

Create your project directory and your environement
```sh
mkdir project
cd project
python3 -m venv .env
```

Clone this repository
```sh
git clone https://github.com/Valentinmf/django-tailwind-boiler-plate
```

Source your envirement
```sh
source .env/bin/activate
```
Install requirements
```sh
pip install -r requirements.txt
```
Go to src folder
```sh
cd src
python manage.py runserver
```
Load tailwindcss
```sh
python manage.py tailwind start
```
To build production css file
```sh
python manage.py tailwind build
```


## License
MIT