# Dashboard notes
**Install virtualenv and virtualenvwrapper**

    $ sudo pip install virtualenv
    $ sudo pip install virtualenvwrapper --ignore-installed six

Create the virtualenv
`$ mkvirtualenv --no-site-packages <virtualenv name>`

Additional requirements:
 - [Homebrew](https://brew.sh/)

**Get your requirements in order**
```
$ git submodule update --init --recursive
$ workon <virtualenv name>  # if your virtualenv is not already activated
$ pip install -r requirements/requirements.txt
```
## Django setup

Install django
`$ pip install django`

Setup the project
`$ django-admin startproject <project name>`

Run the django server
`$ python manage.py runserver <optional port number>`

Create an app within the django project
`$ python manage.py startapp <app name>`

Database migrations
`$python manage.py makemigrations <app name>`
`$python manage.py migrate <app name>`