# hanouta
les étapes en console cmd : 
cd desktop

mkdir django_final

cd django_final

py -3 -m venv venv

venv\scripts\activate

pip install django

django-admin startproject epicerie

cd epicerie

python manage.py startapp project  (ajouter tous ce qui contient le dossier github ici dans le dossier qui va être  créer)

python manage.py startapp accounts (ajouter tous ce qui contient le dossier github ici dans le dossier qui va être  créer)

python -m pip install mysql-connector-python

pip install mysqlclient

python manage.py makemiggrations 

python manage.py migrate

python manage.py runserver 


et ofc créer une db qui s'appelle db_test2 je pense vérifier sur le fichier settings.py
