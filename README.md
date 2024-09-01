# springboot-jpabuddy

docker run --name mysql-container -e MYSQL_ROOT_PASSWORD=Password123 -p 3306:3306 -v /Users/thiru/projects/docker-volume:/var/lib/mysql -d mysql:latest

docker exec -it mysql-container mysql -u root -p

create database javatechie;

http://localhost:8080/  
http://localhost:8080/products  
http://localhost:8080/customers