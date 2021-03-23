# JavaServer
A Server made in Java with as few external dependencies as possible

Dependencies used

Postgres Java Connector - To connect to Postgres: https://jdbc.postgresql.org/

Classes: 

Server - main class mostly used to tell the server which routes to accept

Router - actually directing the request and sending either html/css/javascript/json and creating threads to interact with the database

Database - the part where we interact with the database by using functions called based on the API endpoint with the /users prefix

JSONObject - used to turn Strings into JSON objects and back into JSON strings

Utils - used for File Reading, setting up static content, and getting the info from our .env file

User - a schema template for users, not yet completed nor implemented

Database used: PostgresSQL


To compile:

make

To run:

java -jar target/JavaServer-1.0.jar
