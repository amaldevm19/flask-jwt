### Flask-JWT Authentication
Thanks to Alpha@GeekForGeeks <br/>
This Repository is based on ["Using JWT for user authentication in Flask"](https://www.geeksforgeeks.org/using-jwt-for-user-authentication-in-flask/#:~:text=To%20do%20that%2C%20change%20the,authetication%20with%20JWT%20in%20Flask).  

### Solved problems while implimentation
Some changes in requirements.txt.  

Faced problems with Flask-SQLAlchemy==2.4.1 so updated to 2.5.1 and updated pyJWT.  

["Removed .encode("UTF-8") at line 113"](https://stackoverflow.com/questions/28583565/str-object-has-no-attribute-decode-python-3-error).  

Line at 54 modified ["data = jwt.decode(token, options={"verify_signature": False})"](https://stackoverflow.com/questions/59425161/getting-only-decoded-payload-from-jwt-in-python).  

##### Added 
.gitignore -  for ignore git files.  
.env - for loading environment variables

#### Data base
start the python3 interpreter in your terminal. You can do that by typing python3 in your terminal.
```
    from app import db
    db.create_all()
```





