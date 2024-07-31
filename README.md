# Match

# Installation
- ``pip3 install -r requirements.txt``
- ``uvicorn main:app --reload ``
- create user
  ``curl -X POST "http://127.0.0.1:8000/users/" -H "Content-Type: application/json" -d '{"name": "Deepak Kumar", "email": "deepakkumar@example.com"}'``
- get user
    ``curl -X GET "http://127.0.0.1:8000/users/1" ``
- get users
    ``curl -X GET "http://127.0.0.1:8000/users/" ``
- get matches
    ``curl -X GET "http://127.0.0.1:8000/users/1/matches"``
