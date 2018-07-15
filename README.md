# Flask Restful API
A simple Flask Restful API using Flask-restful

## Description
- A simple Flask Restful API with following endpoints:
    - /add : **POST method**
    - /subtract : **POST method**
    - /multiply : **POST method**
    - /division :  **POST method**

- Posted data format
```
{
    "x": 12,
    "y": 20
}
```

- Response format
```
{
    "Message": <answer>,
    "Status Code": 200
}
```


## Dependencies
- Python
- Flask
- flask-restful

## Installing dependencies
* pip install -r requirements.txt

## How to run
* Clone the repo
* $ cd flask-restful
* $ export FLASK_APP=app.py
* $ flask run

