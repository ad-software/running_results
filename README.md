# running results
Open source system to manage running result for sports clubs
* Python
* Django framework
* Docker

Please use the develop branch as the target for pull requests for ongoing development.

## Status
Development phase

## Features
* Import of data
* Export of data
* Administration of user for the gathering of the data
* Public access to
* record list
* Annual record list
* Annual result lists of every distance and for age groups
* List of events

## Requirements
requirements.txt

and ...

## Documentation
CCS with Bootstrap

## Tutorial
https://github.com/ad-software/running_results/wiki/Tutorial

# Quick Start
'$ git clone https://github.com/ad-software/running_results???'
'$ cd running_results'

Edit .env files
* .env
* running_results/.env

```
$ pip install --upgrade virtualenv
$ python3 -m venv env
$ source env/bin/activate

(env) $ pip3 install -r  requirements.txt
(env) $ python manage.py
```

## Environment setup
Create the file running_results/.env with the following parameter

```
ALLOWED_HOSTS=
DB_NAME=
DB_USER=
DB_PASSWORD=
DEBUG=
SECRET_KEY=
```

If DEBUG equals "True", ALLOWED_HOSTS can be empty.

For local testing use: localhost,127.0.0.1

## Database

### Database Tables
Now run migrations to create database tables for the apps.
'docker-compose exec web python manage.py makemigrations'
'docker-compose exec web python manage.py migrate'

## Admin User
Create an admin superuser:
'python manage.py createsuperuser'

## Language Settings

## Getting Help

## Contributors

## Demo
