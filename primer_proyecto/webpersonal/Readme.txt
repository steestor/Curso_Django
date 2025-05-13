Recuerda!
El entorno en la terminal hay que activarlo manualmente:
    pipenv shell

Ejecutar django:
    python manage.py runserver

Como hemos añadido el siguiente scrip en el Pipfile:

[scripts]
webpersonal = "python webpersonal/manage.py runserver"

Ahora podemos ejecutar lo siguiente para poner en marcha el proyecto: pipenv run webpersonal