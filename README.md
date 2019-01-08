## Dashboard notes

**Setting up your virtualenv**

Install virtualenv and virtualenvwrapper

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
