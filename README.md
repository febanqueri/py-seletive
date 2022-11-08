# py-seletive
 #pyLAB 2022



### Criando o ambiente virtual:
> Linux
> * python3 -m venv venv
> Windows
> * python -m venv venv

### Ativando o ambiente virtual:
> Linux
> * source venv/bin/activate
> Windows
> * venv\Scripts\Activate

### Caso retorno algum erro, tente o comando abaixo e realize o procedimento novamente: 
> Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

### Instalação Django e bibliotecas:
> pip install django
> pip install pillow

[Django](https://www.djangoproject.com/)
[Pillow](https://pillow.readthedocs.io/en/stable/)

### Criando o projeto em Django
> django-admin startproject NOME_DO_PROJETO.

### Iniciando o projeto com o Django:
> python manage.py runserver

### Criando um app:
> python manage.py startapp empresa


### Extensão para o VS Code (SQLite):
> Name: SQLite Viewer
> Id: qwtel.sqlite-viewer
> Description: SQLite Viewer for VSCode
> Version: 0.1.5
> Publisher: Florian Klampfer
> VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=qwtel.sqlite-viewer

### Para realizar um checkup das Models (Tabelas do Banco) criadas:
> python manage.py makemigrations

### Para realizar um "commit" para o Banco:
> python manage.py migrate