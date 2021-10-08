# Project to Monitor Available COVID Resources

## Stack Info

#### Stack:
1. Frontend : Vanilla (HTML5, CSS3, JS) + Bootstrap
2. Backend : Django
3. Database: PostgresSql


#### About the Project

1. This a web application to manage covid resources like vaacine,beds,oxygen cylinders etc..
2. There are mainly 4 users 
    - Admin who will manage user access and can add different locations as well as can register different organizations to contribute in managing resources
    - guest user, who can just visit our site and check the availability of Resources and can also add resources which will be only displayed when it is    
      verified by any organization
    - A organization user, who can verify avaialble resources contribute by guest, can add resources and can modify resources
    - A Head of Organization Management, who will register, manage access of organization users, can also add location, category and sub category of 
      resources. 
3. To Run this project

    - download the zip file extract it
    - cd in extracted folder
    - make a virtual environment
        - python -m venv venv
    - activate venv
        - source venv/bin/activate
    - install dependencies
        - python -r install requirements.txt

    - migrate database
         - python manage.py makemigartions
         - python manage.py migrate

    - change data base credentials in settings.py in the folder covrm
     

