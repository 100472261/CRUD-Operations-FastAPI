# FastAPI-project

docker run --name fastapi-postgres -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:14.17

docker start fastapi-postgres

docker exec -it fastapi-postgres psql -U postgres

\l

postgres=# create database fastapi_database;
CREATE DATABASE
postgres=# create user myuser with encrypted password 'password';
CREATE ROLE
postgres=# grant all privileges on database fastapi_database to myuser;
GRANT