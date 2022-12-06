## Django Best Practices: Custom User Model

In real world most likely we will have to create customized user models instead of use th Django's built-in models.

### set up

- set virtual environment venv.
- Install Django
- make a Django project
- create an Django app
- test runserver


### Custom user model

- update settings.py
- create a ```CustomUser``` model
- create new ```UserCreation``` and ```UserChangeForm```
- update the admin

### Create superuser
used to log in/out admin.

### Templates/Views/URLs

- updating settings.py to create a project-level templates directory. 
- create .html in templates folder
- url.py: creates paths.
- test server

<br>

<p> 

  Keeping all user related information in one model removes the need for additional or more complex database queries to retrieve related models. 
  On the other hand, it may be more suitable to store app-specific user information in a model that has a relation with your custom user model. 
  That allows each app to specify its own user data requirements without potentially conflicting or breaking assumptions by other apps. 
  It also means that you would keep your user model as simple as possible, focused on authentication, and following the minimum requirements Django expects custom user models to meet.
  
</p>

