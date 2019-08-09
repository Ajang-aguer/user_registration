This is a basic django registration app.

# Features:
1. User can register and create an account
2. Users can signin to their account
3. Users can logout

# Tech Stack:
1. Python >= 3.6.5
2. Django==2.2.4
3. sqlite

# Cloning and running the app:

1. Clone this repository into your local machine using the terminal (mac) or Gitbash (PC)
2. CD to the folder
To setup a local development environment:

## For Mac

```bash
virtualenv venv            # create a virtualenv
source venv/bin/activate   # activate the Python virtualenv 
```

## For Windows

```bash
virtualenv venv            # create a virtualenv
venv\scripts\activate   # activate the Python virtualenv 
```


or with [virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/en/latest/),

```bash
mkvirtualenv -p python3 {{project_name}}   # create and activate environment
workon {{project_name}}   # reactivate existing environment
```

## Install the requirements file: 

```bash 
pip install -r requirements.txt 
```

## Migrate: 

```bash 
python manage.py migrate 
```

## Start the server: 

```bash 
python manage.py runserver
```