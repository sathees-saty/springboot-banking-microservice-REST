# springboot-banking-microservice-REST
Banking Application using Spring Boot
<html>
<br>
Create Springboot project with below dependencies:
<br>
Dependencies: Spring Web, Spring Data JPA, postgresql Driver, and Lombok
<br>
During the server start up . table is auto created due to configuration added into application.properties
<br>
  spring.jpa.hibernate.ddl-auto = update
<br>
  Refer below log: table auto created in postgresql DB
<br>
  Hibernate: create table account (id bigserial not null, account_holder_name varchar(255), balance float(53) not null, primary key (id))
<br>
  Run the Application as Spring boot App
<br>
  Test the application in Postman
<br>
    1. Create a new bank account: HTTP Method: POST URL: http://localhost:8080/api/accounts 
<br>
   Sample Request Body:
{
    "accountHolderName": "Kumar",
    "balance": 1000.00
}
<br>
  <img src="https://github.com/sathees-saty/springboot-banking-microservice-REST/assets/65384711/6a96e652-8f49-4e01-9550-6dc3eb63a17f" alt="J" width="600" height="300"/>
  ![image](https://github.com/sathees-saty/springboot-banking-microservice-REST/assets/65384711/6a96e652-8f49-4e01-9550-6dc3eb63a17f)

<br>

</html>

