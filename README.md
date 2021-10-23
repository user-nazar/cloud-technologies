# Cloud technologies

Use of AWS services:

* EC2;
* RDS;
* Route53.

# Open the necessary ports to run the application

* Security groups:

![image](https://user-images.githubusercontent.com/57871748/138553599-fc719afc-3ee1-4878-956b-4c5d73bfde23.png)

If a database communication error occurs, you must add a rule to open port 3306.

# RDS

To connect to the database, you must specify its endpoint.

* Check connection: mysql -h endpoint-name -u root -p .

![image](https://user-images.githubusercontent.com/57871748/138554320-cd6c9a6e-e70e-4e83-a0cd-76054e9b225a.png)

# Apache HTTP server

This server starts when you enter your own domain. This server is an integral part of displaying the application service.

![image](https://user-images.githubusercontent.com/57871748/138554361-6469e981-c3a9-4124-a33a-cd318ab33a8f.png)

# Swagger 

* http://domain-name:8080/swagger-ui.html .

* Swagger is used in conjunction with a set of open source software to design, create, document, and use RESTful web services. 
* Swagger includes automated documentation, code generation and testing.


