# CREACION DE ENTORNO VIRTUAL CON CONDA

---

$ conda create -n app_pp_c1  python=3.11

# OTRA OPCION
---

$ virtualenv -p /usr/bin/python3.11 my_env

# COMANDO DJANGO
---

$ pip install django

$ django-admin startproject Proyecto1

$ cd Proyecto1

$ python manage.py help

$ cd Proyecto1

List: 
* init.py ,settings.py, urls.py, wsgi.py


# ACTIVAR EL PROYECTO

---
- python manage.py migrate
- python manage.py runserver

# INSTALA EL PAQUETE Bootstrap 4

$ pip install django-bootstrap4

# EDITAMOS ARCHIVOS settings.py y agregamos Bootstrap en la parte de INSTALLED_APPS
```
 INSTALLED_APPS = [
     'django.contrib.admin',
     'django.contrib.auth',
     'django.contrib.contenttypes',
     'django.contrib.sessions',
     'django.contrib.messages',
     'django.contrib.staticfiles',
     'bootstrap4', # NUEVA LINEA
 ]
```
