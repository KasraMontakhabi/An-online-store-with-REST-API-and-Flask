
# An online store with REST API and Flask
This is a simple online store simulation made with Flask, Flask_RESTful, Flask_JWT, SQLAlchemy.
## Packages
* [Flask](https://flask.palletsprojects.com)
* [Flask_RESTful](https://flask-restful.readthedocs.io/en/latest/)
* [Flask_JWT](https://pythonhosted.org/Flask-JWT/)
* [Flask_JWT_extended](https://flask-jwt-extended.readthedocs.io/en/stable/)
* [SQLAlchemy](https://www.sqlalchemy.org/)
## Setup
1. Clone this repository.
2. Install requirement packages:

Flask:
```bash
pip Install flask
```
Flask_RESTful:
```bash
pip Install flask-restful
```
Flask_JWT and Flask_JWT_extended:
```bash
pip install flask-JWT
pip install flask-JWT-extended
```
3. Go to the project directory and run app_k.py
```bash
python app_k.py
```

4. You can use [Postman](https://www.postman.com/) to test the API. Endpoints are listed in the following part.

## Tasks 
1. Registers a user
```http
POST http://127.0.0.1:5000/register
```
2. Login
```http
POST http://127.0.0.1:5000/login
```
3. Add store
```http
POST http://127.0.0.1:5000/store
```
4. Add items 
```http
POST http://127.0.0.1:5000/item
```
5. Get store
```http
GET http://127.0.0.1:5000/store
```
6.Get items
```http
GET http://127.0.0.1:5000/item
```
