Este proyecto consiste en dos partes principales: un backend con Django y un cliente con React.

## Backend - Djangorestframework

Este es el backend del proyecto, construido con Django y djangoFramework. Proporciona la API que el cliente consume (cómo las peticiones GET, POST, PUT, DELETE).

### Requisitos

- Python 3.12.5
- Django
- djangorestframework

- ### Instalación

   1) git clone [https://github.com/NathansinDrake/Django-api/edit/main/](https://github.com/NathansinDrake/Django-api.git)

   2) Navega al directorio del proyecto:
     ejemplo: cd backend o cd django-api

   3) Crea un entorno virtual:
      python -m venv venv (en visual studio code puedes usar la tecla f1 y seguido buscar python:Selec Interpreter, buscar el entorno que te diga python{3.1x.xx} venv y hacer
      click en él, también puedes ver que en la parte izquierda te saldrá una estrella o un texto que dice recommended, hacer click ahí)

   4) Ejecuta las migraciones y el servidor:
      python manage.py migrate
      python manage.py runserver

- Siguiendo estos pasos sólo quedaría clonar el cliente, construido con Vite usando React. Consume la API proporcionada por el backend.

  ### Requisitos

- Node.js v20.17.0
- npm o yarn  

  
