# Desafios

### PostgreSQL
```
docker container run -d -p 5432:5432 --name postgresdb -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker postgres
```

### MySQL
```
docker container run -d -p 3306:3306 --name mysqldb -e MYSQL_ROOT_PASSWORD=root_pwd -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd mysql
```

### MongoDB
```
docker container run -d -p 27017:27017 --name mongodb -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
```
