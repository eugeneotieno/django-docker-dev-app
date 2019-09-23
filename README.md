# django-docker-dev-app
Docker development environment for Django app

1. Clone the app

2. cd into the project

In terminal:
3. $ docker build .

4. $ docker-compose build

5. $ docker-compose run ddda sh -c “django-admin.py startproject app .”

6. $docker-compose up

Then visit http://localhost:8000/

7. $ docker-compose exec ddda python manage.py migrate

From now onwards you will run django commands as the above command, adding your command after the service name ddda.

That’s it for now. I know it I simple and there are a lot of features we have not covered like database but this is a start!
