#

## Create your virtual environment

Run :

- `virtualenv -p python3 env`
- `source env/bin/activate`
- `pip install -r requirements.txt`

## Launch the db

You need to have docker-compose installed

- use the env.template to create an env file
- run `docker-compose up`

## Run the migrations

- python manage.py migrate
