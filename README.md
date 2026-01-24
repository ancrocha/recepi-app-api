# recepi-app-api
Recepi API project to learn Django Rest framework


## Commands
docker-compose build
docker-compose up

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose run --rm app sh -c "python3 manage.py runserver 0.0.0.0:8000"