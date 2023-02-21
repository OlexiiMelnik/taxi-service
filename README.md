# 🚖taxi-service🚖
# Project description👍
A web application that supports authentication is used in compliance with the SOLID, CRUD principle and Dependency Injection.
# Business value
This application is designed for taxi service. The service keeps records of cars that a taxi company has, as well as records of drivers and which drivers operate which cars. A very convenient service that simplifies accounting.
# Features
- registration of drivers
- authentication of drivers
- displaying the list of drivers
- removing drivers
- displaying the driver's car list
- registration of cars
- displaying the list of cars
- removing cars
- adding a driver to the car
- registration of manufacturers
- displaying the list of manufacturers
- removing manufacturers
- driver logging out
# Project structure
Project used 3-tier architecture:

1.Data access tier -> handled by DAO;

2.Business logic tier -> handled by Service;

3.Presentation tier -> handled by Controllers and JSP pages.

![img](https://user-images.githubusercontent.com/111267682/220085546-10bdddea-a42f-4402-915a-6ecd37e54552.png)

# Technologies
1.Maven

2.JDBC

3.MySQL 8.0

4.Tomcat 9.0.71

5.Java Servlet

6.Java programming language (JDK 1.8)

# Instructions to run my project
• To get the actual parameters of the database tables, run script from the resources/init_db.sql file in the Workbench.
• Configure connection to your database in util package
• Add your local server in the configurations. Will be better using Tomcat 9.0.71.
