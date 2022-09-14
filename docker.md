# mysql 5.7
docker run --name mysql57 -p 3306:3306 -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_ROOT_HOST="%" -d mysql:5.7 --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci --default-time-zone=+8:00  

# mysql 8.0.30
docker run --name mysql8 -p 3307:3306 -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_ROOT_HOST="%" -d mysql:8.0.30 --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci --default-time-zone=+8:00  
