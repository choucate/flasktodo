# flasktodo
Todo App with Flask for Superloop

For styling semantic-ui is used.

Setup
Create project with virtual environment in its own directory

$ mkdir flasktodo
$ cd flasktodo
$ python3 -m venv venv
Activate it

$ . venv/bin/activate

Install Flask

$ pip3 install Flask
$ pip3 install Flask-SQLAlchemy

Set environment variables in terminal in order to facilitate execution

$ export FLASK_APP=app.py
$ export FLASK_ENV=development
or on Windows

$ set FLASK_APP=app.py
$ set FLASK_ENV=development
Run the app

$ flask run
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

