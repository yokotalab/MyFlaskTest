# MyFlaskTest
testing Flask on Windows

## Memos for Windows env

- User's Guide
  - https://flask.palletsprojects.com/en/1.1.x/

- Installation
  - https://flask.palletsprojects.com/en/1.1.x/installation/

```
mkdir myproj
cd myproj
python -m venv venv
venv\Scripts\activate
pip install Flask
```

- To start development:

```
cd myproj
venv\Scripts\activate
```

- Run The Application
  - https://flask.palletsprojects.com/en/1.1.x/tutorial/factory/#run-the-application

```
set FLASK_APP=flaskr
set FLASK_ENV=
flask run
```
(On Windows, FLASK_ENV=development does not work correctly)

- URL for test:
  - http://localhost:5000/
