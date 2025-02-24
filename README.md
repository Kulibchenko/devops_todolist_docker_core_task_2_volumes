# Django-Todolist

Django-Todolist is a todolist web application with the most basic features of most web apps, i.e. accounts/login, API and (somewhat) interactive UI.

---
CSS | [Skeleton](http://getskeleton.com/)
JS  | [jQuery](https://jquery.com/)

## Explore
Try it out by installing the requirements. (Works only with python >= 3.8, due to Django 4)

    pip install -r requirements.txt

Create a database schema:

    python manage.py migrate

And then start the server (default: http://localhost:8000)

    python manage.py runserver


Now you can browse the [API](http://localhost:8000/api/)
or start on the [landing page](http://localhost:8000/)


## Run MySQL
  To run mysql container with volume attached use next command

    docker run -d -p 3306:3306 --name my-mysql -v my-mysql-data:/var/lib/mysql mysql-local:1.0.0

## Run app todolist
  To run container with app todolist use next command 

    docker run -p 8080:8080 --name todoapp todoapp:2.0.0

## Link to app image
  https://hub.docker.com/repository/docker/valerakb/todoapp/

## Accessing the application via a browser
For accessing the application via a browser go to [[link](http://localhost:8080/)]
