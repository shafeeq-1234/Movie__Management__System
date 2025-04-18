# Movie Management System
Movie Management System is a web application built using Django along with MySQL database, which allows users to filter, view and making reservations for various different movies. This is a project made for Database Systems Lab course. Full details regarding schema and features can be found in the project report.

# Instructions 
- Ensure you have MySQL and Python3 installed.
- Run the following:
```
pip install -r requirements.txt
```
# Instruction to Connect to Mysql Database
* Create a Database in MYSQL
```
# sql
create database movie;
``` 
* Terminal Commands
```
cd Movie_Management_System
```
```
cd Movie_Management_System
```
* Rename databaseconfig_example.py to databaseconfig.py
* Enter your MYSQL username & password
# Make Migrations
```
python manage.py migrate
```
# Run Server
```
python manage.py runserver
```
- Then visit [127.0.0.1:8000/](127.0.0.1:8000/)

# Instructions to Create admin
- Run the following:
```
python manage.py createsuperuser
```
- Then visit [127.0.0.1:8000/admin](127.0.0.1:8000/admin)

# Tech Stack 
- Frontend : HTML, CSS and JavaScript
- Backend : Django
- Database : MySQL 