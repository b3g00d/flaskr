==============
Flask tutorial
==============

Introducing
-----------

- I am following Flask tutorial: http://flask.pocoo.org/docs/0.11/tutorial/folders/
- /flaskr is the main directory for running file
- /static folder is available to users of the application via HTTP. This is the place where CSS and Javascript files go.
- /templates: Inside the templates folder, Flask will look for Jinja2 templates. The templates you create later on in the tutorial will go in this directory.
- /tmp folder is containing database

Running
-------
- First: **export FLASK_APP=/your/path/flaskr/flaskr.py**
- Optional: **export FLASK_DEBUG=1** - for debugging
- Second: **sqlite3 /your/path/flaskr/tmp/flaskr.db < /your/path/flaskr/schema.sql**
- Third: **python3** -> **from flaskr import init_db** -> **init_db()** -> **exit**
- Fourth: **flask run**
