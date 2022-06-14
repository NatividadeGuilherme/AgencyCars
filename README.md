# AgencyCars
Hands On about docker

Command to up the database
docker run -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=agency -p 8083:3306 -d mysql:latest
