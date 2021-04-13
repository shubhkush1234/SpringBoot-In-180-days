## Spring Basics, Spring Boot , Micro services ##

Pre requisites:

Core Java, OOPS, JDBC

## What is prog lang , technology and framework? ##

- C, C++, Java : prog lang
- JDBC, Servlet, JSP , EJB etc : Technlogies
- Spring, Hibernate, Struts, JSF: Frameworks.

Technology API gives:

- Interfaces --> representing rules

(When class implements an interface, all the methods of interface must be implemented)

- Concrete classes --> representing Guidelies

(You may or may not use super class methods in subclass)

- abstract classes --> representing both rules and guidelines

()

## From Java 8 ##

- Interfaces also represent rules and guidelines.

## Spring JDBC ##

Create JDBC template class object (takes care of common logics)

- Send and executes SQL Queries in DB software.
- Gather results and process results.
- So, there is no boilerplate problem, programmers just need to develope only app specification logics.


Day-2
======

# Different types of Java Framework #

## Web application frameworks/ Web frameworks / MVC Architecture  ##


- Provides abstraction  on servlet , jsp technologies and simplifies the mvc architecture based java web application development.

struts --> from Apache
Spring MVC --> from interface21 (Pivotal Softwares)
JSF --> Oracle
Tapstrey --> Adobe

## ORM Framework  ##

- Provides abstraction on JDBC Technology and simplifies to develope object based db software independent persistent logic.

Eg:

- Hibernate --> from redHat
- IBatis --> from Apache
- Eclipse Link --> from Eclipse
NOTE : Spring ORM is not giving its own ORM framework, but it is providing Spring ORM , Spring data JPA modules, providing abstraction on other ORM frameworks, mainly Hibernate.

## Application Framework  ##

- Provides abstraction on multiple Java, JEE technologies and simplifies all kinds Java/JEE app development.

Eg: Spring --> by Pivotal 


- Spring framework provides abstraction on multiple Java, JEE technolgies like JDBC, JNDI Servlet JSP , EJB Java Mail, JMS etc.

- Using spring we can develope standalone app, web app, distributed apps, enterprise app etc.

- Using Spring, we can develope presentation logics, business logics, persistence logics, integration logics etc.


Eg: <browser> --> <FlipKart> --> <Paypal> --> <Visa> --> <SBI>

   --web app---Distributed app------Distributed app------Distributed app---

   - Web app is a client server app where client is browser and server is software app.

- We can develope Spring Apps in 4 approaches:

1. Using XML driven configs
2. Using Annotation driven configs
3. Using 100% code driven configs
4. Using Spring Boot env.










































































