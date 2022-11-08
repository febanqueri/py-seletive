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