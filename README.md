# python-flask-crud-api

Flask is a simple, yet very powerful Python web framework.
This is a simple user registration rest api application.

#need flask...
sudo pip install flask_table
sudo pip install flask-mysql
 
#How to run...
python main.py
Running on http://127.0.0.1:5000/

#Try bellow api calls...
http://127.0.0.1:5000/createuser
{
	"name": "name",
    "email": "email@gmail.com",    
    "password": "password"
}

http://127.0.0.1:5000/updateuser
{
	"id": "id",
	"name": "name",
    "email": "email@gmail.com",    
    "password": "password"
}

http://127.0.0.1:5000/users

http://127.0.0.1:5000/getuser/1

http://127.0.0.1:5000/deleteuser/1
