# django-with-postgre-heroku
This is a sample how to connect django application to postgre on heroku

### How to run this application on my local machine
1. Install `pipenv` on your machine using `pip`
```
pip install pipenv
```
2. Install application libraries using pipenv 
```
pipenv install --system
```
3. Run `migrations`, `migrate`, and `runserver`
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver 0.0.0.0:available_port
```
