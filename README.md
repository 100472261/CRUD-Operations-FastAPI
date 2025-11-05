<h1 align="center"> ⚡ CRUD operations with FastAPI </h1>
<p align="justify"> Aplicación backend construida con FastAPI que permite realizar operaciones CRUD (Create, Read, Update, Delete) sobre una BD PostgreSQL. </p>
<h2 align="left"> ● Pasos: </h2>
<p align="justify">1. En una terminal se ejecuta el comando <code>docker run --name fastapi-postgres -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:14.17</code> para crear un contenedor PostgreSQL con Docker.</p>
<p align="justify">2. Se inserta el comando <code>docker exec -it fastapi-postgres psql -U postgres</code> para acceder a la consola interactiva de PostgreSQL dentro del contenedor <code>fastapi-postgres</code>.</p>
<p align="justify">3. Se crea una base de datos mediante el comando <code>create database fastapi_database;</code>.</p>
<p align="justify">4. Se crea un usuario mediante el comando <code>create user myuser with encrypted password 'password';</code>.</p>
<p align="justify">5. Se le añaden permisos al usuario para que pueda realizar operaciones sobre la base de datos mediante el comando <code>grant all privileges on database fastapi_database to myuser;</code>.</p>
<p align="justify">6. En una nueva terminal se introduce el comando <code>uvicorn main:app --reload</code> para ejecutar la aplicación FastAPI.</p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
