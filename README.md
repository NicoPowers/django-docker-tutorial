# django-docker-tutorial
Following [this guide](https://learndjango.com/tutorials/django-docker-and-postgresql-tutorial) for docker & postgres integration

Using [this book](https://www.amazon.com/Django-Professionals-Production-websites-Python/dp/1081582162) to learn django for production apps. This repo reflects my progress through that book.

## Getting setup for development
1. `docker-compose up -d`
   1. If changes were made to the `Dockerfile` or `docker-compose.yml`, run `docker-compose up -d --build`
2. `docker-compose exec web manage.py runserver`

