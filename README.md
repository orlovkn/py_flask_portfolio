## installition

[Quickstart](https://flask.palletsprojects.com/en/1.1.x/quickstart/#)

### step 1
```
py -3 -m venv app
```

### step 2
```
app\Scripts\activate
```

### step 3
```
pip install Flask
```

### step 4
```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
```

### step 5
```
set FLASK_APP=app.py
```

### step 6
```
flask run
```

### step 7
```
set FLASK_ENV=development
```

### links
[Flask-Request-Data](https://flask.palletsprojects.com/en/1.1.x/quickstart/#accessing-request-data)

[CSV-module](https://docs.python.org/3/library/csv.html)
