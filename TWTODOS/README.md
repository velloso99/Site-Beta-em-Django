## Requisitos 
# Python 3 ou superior == conferir a versão: Python --version
# Python 5 ou superior -  Conferir a versão do Django: django-admin --version

## Sequencia para criar o projeto

Criar ambiente virtual.
...

python -m venv venv
...

Ativar o ambeinte virtual.
...

venv\Scripts\activate
...

Instalar Django
...

pip install Django
...

Criar um projeto
...
django-admin startproject admin .

Gerar o arquivo com as dependencias.
Após instalar a depedencia , execute o comando abaixo

pip freeze > requirements.txt
...

execute as migration.

python manage.py migrate

Rodar o projeto.

python manage.py runserver
http://127.0.0.1:8000/

Criar o Super usuario

python manage.py createsuperuser
http://127.0.0.1:8000/admin
...

criar um app

python manage.py startapp nome-do-app
...

python .\manage.py startapp courses