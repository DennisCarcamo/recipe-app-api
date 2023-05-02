# recipe-app-api
'create new app'
docker-compose run --rm app sh -c "django-admin startproject app ."
# flake8
'error cheking'

    docker-compose run --rm app sh -c "flake8"
# unit test
docker-compose run --rm app sh -c "python manage.py test"