# Behavior-logging-System
This web application is developed to log the user browsing behavior and then visualizing the user interactions
1.Run the commands in DBscript.txt in MySQL Database(Username:admin,Password:root,Database:adaptive)
2.Steps to load the extension:
  a.Open Google chrome
  b.Go to Customize and Control Google Chrome(Three Vertical Dots)->More tools->Extensions and click on it
  c.Browse the folder to Behaviour-logging-system\extension in the project directory and click OK
3.Please install Python, pip, Python Flask, Pymysql using the following links:
Pip---  https://pip.pypa.io/en/stable/installing/
Flask---- http://flask.pocoo.org/docs/0.12/installation/#pip-and-setuptools-on-windows
Pymysql---http://pymysql.readthedocs.io/en/latest/user/installation.html
4.Run the app.py file in the extracted folder
5.Type in 127.0.0.1:5000/login in Chrome Browser to view the application

Please Note:The visualizations can be seen after logging in interactions for every user.i.e Values in the table 'logactions'
have to be inserted. Otherwise the visualizations will seem to be empty.
