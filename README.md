# recepi-app-api
Recepi API project to learn Django Rest framework.

This app I created while studying the course on Udemy called "Build a backend REST API with Python and Django - Advanced" by Brooke Rutherford.

Core concepts I learned during this course:
- Test Driven Development with Django.
- Github Actions.
- Docker build and compose.
- Mocking test.
- Postgres DB.




## Commands frequently used during the training (personal note)
docker compose build
docker compose up
docker compose run --rm app sh -c "flake8"
docker compose run --rm app sh -c "django-admin startproject app ."
docker compose run --rm app sh -c "python3 manage.py runserver 0.0.0.0:8000"
docker compose run --rm app sh -c "python3 manage.py test"
docker compose run --rm app sh -c "python3 manage.py startapp core"
docker compose run --rm app sh -c "python3 manage.py test && flake8"