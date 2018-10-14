# Polls

This is the Polls project written in Django. It has been written by following
the [Django 2.1
tutorial](https://docs.djangoproject.com/en/2.1/intro/tutorial01/).

## Running the project

Run the project in a virtual environment. 

```shell
git clone https://github.com/tskovlund/django-tutorial.git
cd django-tutorial
virtualenv -p python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
# follow the interactive creation
python manage.py runserver
```
