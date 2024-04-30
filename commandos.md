# CREACION DE ENTORNO VIRTUAL CON CONDA

---

$ conda create -n app_pp_c1  python=3.11

# OTRA OPCION
---

$ virtualenv -p /usr/bin/python3.11 my_env

# COMANDO DJANGO
---
$ django-admin startproject Proyecto1
$ cd Proyecto1
$ python manage.py help
$ cd Proyecto1

List: init.py ,settings.py, urls.py, wsgi.py


# ACTIVAR EL PROYECTO

---
- python manage.py migrate
- python manage.py runserver
