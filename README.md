# quiz


## Project setup
### Setup virtual env and pip.
```
$ virtualenv quiz-env
```
### Activate virtual env
Linux
```
$ source quiz-env/bin/activate
```
Windows
```
> quiz-env\bin\activate
```
### Download packages
```
$ pip install -r requirements.txt
```
### .env
Create .env file or rename .env.local to .env

### Do migration
```
$ python manage.py migrate
```
### Run server
```
$ python manage.py runserver
```


## Docker launch
### Build image
```
docker-compose up --build
```

### Creating \admin\ superuser
```
docker compose exec server python backend/manage.py createsuperuser
```