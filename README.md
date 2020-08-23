# Heart Care
 
Heartcare is a diagonostic management project developed in django. Admin can add doctor, add services, add gallery pictures . User can see doctors profile and also they can make appointment. They can also contact to the heartcare through email.

# Requirements

open requirements.txt file to see requirements

# To install requirements type

pip install -r requirements.txt

# Installing
open terminal and type
simply download using the url

# To migrate the database
open terminal in project directory and type
python manage.py makemigrations
python manage.py migrate
To collect static files
python manage.py collectstatic

# Creating Superuser
To create superuser open terminal and type

python manage.py createsuperuser

# For email sending functionality fill up the information in Your Project setting
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your email'
EMAIL_HOST_PASSWORD = 'your email password'
To run the program in local server use the following command
python manage.py runserver
Then go to http://127.0.0.1:8000 in your browser
