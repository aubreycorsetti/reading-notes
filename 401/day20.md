# Day 20 Notes

## Readings: Django Custom User

### Django Custum User Model

• There are two ways to create a custom user model in Django: AbstractUser and AbstractBaseUser.

> Requirements/Setup:

- update django_project/settings.py

- create a new CustomUser model

- create new UserCreation and UserChangeForm

- update the admin

-Within INSTALLED_APPS add accounts at the bottom. Then at the bottom of the entire file, add the AUTH_USER_MODEL config.

- We need new versions of two form methods that receive heavy use working with users. Stop the local server with Control+c and create a new file in the accounts app called forms.py.

-set the redirect links for log in and log out, which will both go to our home template. Add these two lines at the bottom of the file.

-Create a new project-level templates folder and within it a registration folder as that's where Django will look for the log in template. Put your signup.html template in there.

-create four templates using either the touch command on macOS or your text editor on Windows.

### DjangoX

> Setup

- Install djangox, first clone the repo to your local computer.

- cd into djangox

- create venv

- $ source .venv/bin/activate

- (.venv) $ pip install -r requirements.txt

- (.venv) $ python manage.py migrate

- (.venv) $ python manage.py createsuperuser

- (.venv) $ python manage.py runserver

- Load the site at http://127.0.0.1:8000

- Add environment variables.

- Add gunicorn as the production web server.

- Update the EMAIL_BACKEND and connect with a mail provider.

- Make the admin more secure.

- django-allauth supports social authentication if you need that.

#### Things I want to know more about

I want to know everything about Django! I love it!

#### Sources

[Django Custom User Model](https://learndjango.com/tutorials/django-custom-user-model)

[DjangoX](https://github.com/wsvincent/djangox)

Click to return [Home!](../README.md)
