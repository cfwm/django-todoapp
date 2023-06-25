# django-todoapp
A Django server that provides a task CRUD.

# requirements
Python 3.6
Django

# setting Python env

python3 -m venv env
source env/bin/activate

# django db admin
http://127.0.0.1:8000/admin/login/?next=/admin/
http://127.0.0.1:8000/admin/
# run
python3 manage.py runserver 8000

# routes
http://localhost:8000/todo/list
http://localhost:8000/todo/create
http://localhost:8000/todo/update/$index
http://localhost:8000/todo/delete/$index