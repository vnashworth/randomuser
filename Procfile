web: python manage.py dmp_collectstatic --overwrite; python -m whitenoise.compress staticfiles/homepage/styles; python -m whitenoise.compress staticfiles/homepage/scripts; python manage.py makemigrations; python manage.py migrate; gunicorn randomuser.wsgi --log-file -