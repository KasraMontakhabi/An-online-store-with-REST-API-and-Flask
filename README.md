
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
2. Login and get access token
```http
POST http://127.0.0.1:5000/login
```
3. Add store with a name 
```http
POST http://127.0.0.1:5000/store/<name>
```
4. Add items with a name. Select the corresponding item's store with entering store ID in body.
```http
POST http://127.0.0.1:5000/item/<name>
```
5. Add or update an existing item with name. Select the corresponding item's store with entering store ID in body.
```http
PUT http://127.0.0.1:5000/item/<name>
```
6. Get all items with their corresponding store
```http
GET http://127.0.0.1:5000/items
```
7. Get item by its name
```http
GET http://127.0.0.1:5000/item/<name>
```
8. Get store by its name
```http
GET http://127.0.0.1:5000/store/<name>
```
9. Get all stores
```http
GET http://127.0.0.1:5000/stores
```
10. Get user by user ID
```http
GET http://127.0.0.1:5000/user/<user_id>
```
11. Delete a store by its name
```http
DEL http://127.0.0.1:5000/store/<name>
```
12. Delete an item by its name
```http
DEL http://127.0.0.1:5000/item/<name>
```
13. Delete a user by its user ID
```http
DEL http://127.0.0.1:5000/user/<user_id>
```
