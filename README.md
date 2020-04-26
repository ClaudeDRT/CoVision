These are the lines in terminal that you hav to run once you've endered the first folder in the zip file to be able to locally run the website:

pip install django==2.1.5;
django-admin startproject mysite;
python manage.py startapp main;
python manage.py runserver


(Then head to teh https that it shows if it's running happily to see if the website is running locally)
