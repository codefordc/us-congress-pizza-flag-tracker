# Capitol Flag Pizza Tracker App

In collaboration with Modernization Staff Association.

Flask app proof of concept.

To run:
TODO: https://dev.to/mburszley/an-introduction-to-poetry-2b6n ?
```
conda activate myenv
pip install -r requirements.txt
FLASK_APP=app.py flask run

DEBUG=True FLASK_APP=app.py flask db init
DEBUG=True FLASK_APP=app.py flask db migrate
DEBUG=True FLASK_APP=app.py flask db upgrade
```

### TODOs:
* Work on models on Wed Jan 27 7pm ET.
* Inital migrate of the database.
* Plug some data in there along lines of the (https://www.figma.com/file/Lzq30lUA6N0hevjn8JVU6z/flag-requests?node-id=2%3A4)[Figma]
