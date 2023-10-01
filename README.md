# django-recipe-app-api
Recipe app API built using Django


## Getting Started

1. `docker-compose build`
2. `docker-compose run`
3. Create a superuser `docker-compose run --rm app sh -c "python manage.py createsuperuser"`
4. Head over to 127.0.0.1:8000/admin for Django admin
5. Head over to 127.0.0.1:8000/api/docs for Swagger API docs and to test out the API