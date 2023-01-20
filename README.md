# AgriculturalHousehold_Backend-master


An object-oriented programming paradigm was chosen
for the development of the application. 
When creating the application, a three-tier client-server 
architecture was used. The three-tier client-server architecture
consists of:
* basic client layer - the frontend part of the application that represents the GUI for interacting with the end user and that sends  requests to the middle layer of the application,
* application web server - the middle layer of the application (backend part) in which the complete logic of the application is located and which communicates with the database server and
* database server - stores and provides the necessary data.

The client layer of the application was created using the *Angular*
web application development platform. The program code is written
in the *Visual Studio Code* editor. Code for frontend layer is placed on repository named "AgriculturalHousehold_Frontend-master"
The application web server is created as a *Spring Boot* application written
in the *Java* programming language. The development environment *Intellij IDEA* was used. 
Relational database was benefit which had been created in *Microsoft SQL Server Management Studio*. 
JPA, and his implementation Hibernate, was used for ORM.
In addition to the relational database, Cassandra, colon-oriented NoSql database was used.

Application coordinated architecture of backend was chosen for the implementation of this project. It is the server application that takes care of which database 
is responsible for storing which data. In this example, the application is divided into two modules.
The management of such an application is facilitated because the data manipulated by the modules does not overlap but is specific to the individual module.
