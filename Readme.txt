********* all project file given in zip file format *******
******** Mohammad Shah Alam Tasin ************
#Project Name: CRUD-BITS-FINAL
#User Software :
   IDE: Spring Tool Suite
   Database: MySQL server & Workbench
*** Create a database named studenttable
#Contain package : 
1. demo
  *contain a main class for the project
2.controller
  *contain one controller class to handle all requests
   *contain another controller class for creating REST API to get     student list
3. model
  *contain a model class for creating the table in the database
4. repository
  *contain repository interface for use the built-in       CrudRepository interface
5. Service
   *Contain one interface which has some declaration of some           methods
    *Contain another class that implements the interface

#Application.properties file contain all the necessary code for connecting with the database MySQL server 

#pom.xml file contains all the dependencies that are used in the project 

Used Dependencies:
  *spring-boot-starter-thymeleaf
   *spring-boot-starter-web
   *spring-boot-devtools
   *mysql-connector-java
   *tomcat-jdbc
   *bootstrap
   *webjars-locator-core
   *spring-boot-starter-validation
#The template folder contain three html file for the desgin the responsive front-end by using HTML,CSS,Bootstrap


# The Table named in the database named student  which contains the following fields :  
       i.Id (Integer, Primary key, Auto Increment)
       ii. Name (Varchar, mandatory)
      iii. birthdate (Varchar, mandatory)
      iv. gender (Varchar, mandatory)
       v. note: (Varchar, optional)
      vi.pass : (Varchar,mandatory)
 
# One can get student list as JSON by accessing "http://localhost:8080/api/v1/students/ " Url 
  

