In mysql command line : 

mysql> create database db_example;

mysql> create user 'springuser'@'%' identified by 'ThePassword'; 

mysql> grant all on db_example.* to 'springuser'@'%'; 

mvnw spring-boot:run

mvnw clean package

java -jar target/accessing-data-mysql-complete-0.0.1-SNAPSHOT.jar

localhost:8080/demo/all

In cmd : curl localhost:8080/demo/add -d name=Hafiz -d email=hafiz@gmail.com

localhost:8080/demo/all
