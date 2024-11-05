CREATE
```bash
django-admin startproject mysite djangotutorial
```

START
```bash
py manage.py runserver
```

CREATE MODULE
```bash
py manage.py startapp blog
```

PARA CORRERLO EN PYCHARM SIN PONER COMANDOS
```bash
En PyCharm Community Edition, puedes configurar una Run Configuration para ejecutar tu proyecto Django. Sigue estos pasos:
Abre PyCharm y ve a Run > Edit Configurations... en el menú superior.
En la ventana de configuraciones, haz clic en el símbolo de + y selecciona Python para agregar una nueva configuración.
Completa los siguientes campos:
Name: Ponle un nombre a tu configuración, como Django Server.
Script path: Indica la ruta hacia manage.py en tu proyecto, por ejemplo: /ruta/al/proyecto/manage.py.
Parameters: Escribe runserver para que PyCharm ejecute el comando py manage.py runserver.
```
