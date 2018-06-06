## Running wordpress with docker run

docker run -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=wordpress --name wordpressdb -v "$PWD/database":/var/lib/mysql -d mariadb:latest

## Running wordpress with docker-compose

docker-compose up -d