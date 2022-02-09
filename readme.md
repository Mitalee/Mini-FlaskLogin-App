Directly taken from the tutorial 
```
https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login
```
Install all requirements
```
>> pip install -r requirements.txt
```
To create the db.sqlite table, go into python shell and
```
>> from project import db, create_app, models
>> db.create_all(app=create_app()) # pass the create_app result so Flask-SQLAlchemy gets the configuration.
```

Run the app
```
flask run
```

Index, Login and Profile Pages
![Index](./index.jpg)
![Login](./login.jpg)
![Profile](./profile.jpg)
