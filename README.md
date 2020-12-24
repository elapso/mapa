# mapa
html page with map by django

# setup
  1. apt install libsqlite3-mod-spatialite
  2. apt install binutils libproj-dev gdal-bin
  2. pip install -r requirements.txt
  2. python manage.py makemigrations
  2. python manage.py migrate
  2. python manage.py createsuperuser
  
# test run
by unicorn
gunicorn --bind 127.0.0.1:3333 bob_map.wsgi

#wsgi setup links
  1. https://simpleit.rocks/python/django/set-up-ubuntu-to-serve-a-django-website-step-by-step/
  2. 
