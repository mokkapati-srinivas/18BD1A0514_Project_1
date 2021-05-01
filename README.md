# Hospital Management System (REST API)

## For running the application: 

1. Run server.js and on postman pass a POST request at port number 100 with path /login.
2. In body -> raw -> JSON, pass a json text with {"username": "admin", "password": "password"}.
3. With this you'll be able to get the token. This token is used to login to the system.
4. Now, pass a GET request with /login and in 'headers' pass the 'Authorization' key as 'Bearer <generated token>'(without any single quotes). With this you get the access to the system.
5. Now stop server.js and start index.js and this listens at port number 1100.
6. Now, you can get, add, update and delete the ventilator and hospital details.
7. For add, update and delete pass the data in body -> raw -> JSON.
