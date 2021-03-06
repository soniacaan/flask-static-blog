title: No more static thoughts
date: 2013-08-27



Flask is a microframework for Python based on Werkzeug, Jinja 2 and good intentions. And before you ask: It's BSD licensed!
Latest Version: 0.12.2
Flask is Fun
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"
And Easy to Setup
$ pip install Flask
$ FLASK_APP=hello.py flask run
 * Running on http://localhost:5000/

Interested?
Download latest release (0.12.2)
Read the documentation or download as PDF
Join the mailinglist
Fork it on github
Add issues and feature requests
What’s in the Box?
built-in development server and debugger
integrated unit testing support
RESTful request dispatching
uses Jinja2 templating
support for secure cookies (client side sessions)
100% WSGI 1.0 compliant
Unicode based
extensively documented
What do Flask Apps look like?
If you are looking for some example code of applications written with Flask, have a look at the sources of the examples on github:

flaskr — a microblog
minitwit — a twitter clone
this website — static pages + mailinglist archives
Contribute
Found a bug? Have a good idea for improving Flask? Head over to Flask's github page and create a new ticket or fork. If you just want to chat with fellow developers, visit the IRC channel or join the mailinglist. You can also directly add issues and feature requests to the issue tracker.