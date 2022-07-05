# Polling-website
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
python== 3.5 or up and django==2.0 or up

Installing
open terminal and type
git clone https://github.com/aayushirai9900/Polling-website.git

or simply download using the url below
https://github.com/aayushirai9900/Polling-website.git

To migrate the database open terminal in project directory and type
python manage.py makemigrations
python manage.py migrate

To use admin panel you need to create superuser using this command 
python manage.py createsuperuser
To run the program in local server use the following command 
python manage.py runserver

Then go to http://127.0.0.1:8000 in your browser
