# Shopping-Cart
![code quality score](https://www.code-inspector.com/project/20644/score/svg)   ![code grade](https://www.code-inspector.com/project/20644/status/svg)

# Team-2-Shopping-Cart-Project

# Folder Structure

Folder |  Description
------------- | -------------
1 *shoppingcart* | Demo project implemening front-end
2 *Team_2_ShoppingCart*  | Demo project implemening Login and Registration
3 *Team_2_ShoppingCart_Final* | Final Shopping Cart Project using Spring Boot and Hibernate.

# Contributors List

Name                     |  PS No.   | Features                         | Issues Raised       | Issues Resolved
-------------------------|-----------|----------------------------------|---------------------|---------------------------------
`1) Abhishek Vithal`     | 99003612  |4 W's and H and Feasibility Study | on design           | design issue is resolved
`2) Kricha Sahu`         | 99003587  |Database Conectivity              | on db connectivity  | connectivity issue is reolved
`3) Shaloo Kumari`       | 99003603  |SWOT Analysis                     | on requirement      | requirement issue is resolved
`4) Polimera Sai Khanith`| 99003599  |Behavioral Diagram                | on sequence diagram | Sequence Diagram is resolved
`5) Akash Singh`         | 99003615  |Structural Diagram                | on Class Diagram    | Class Diagram is resolved

# High Level Design

## Class Diagram

![Class Diagram](https://github.com/PS99003587/Team-2-Shopping-Cart-Project/blob/main/Team_2_ShoppingCart_Final/design/Structural%20Diagrams/Class%20Diagram.png)

# Low Level Design

## Sequence Diagram 

![Sequence Diagram](https://github.com/PS99003587/Team-2-Shopping-Cart-Project/blob/main/Team_2_ShoppingCart_Final/design/Behavioral%20Diagram/Sequence%20Diagram%20for%20online%20customer.png)

## State Diagram

![State Diagram](https://github.com/PS99003587/Team-2-Shopping-Cart-Project/blob/main/Team_2_ShoppingCart_Final/design/Behavioral%20Diagram/State%20Diagram%20for%20Customer.png)

## Collaboration Diagram

![Collaboration Diagram](https://github.com/PS99003587/Team-2-Shopping-Cart-Project/blob/main/Team_2_ShoppingCart_Final/design/Structural%20Diagrams/Collaboration%20Diagram%20for%20user%20registration.png)

## Challenges

**MySQL:**

- We faced some problems while working MySQL like using 'Primary Key' that we created in database which we solved by using a keyword called ‘primary key’ in the column.
- The other problem we faced was using 'Foreign Key' and we solved it by using a keyword called ‘foreign key’ which is used to link two tables in our database.
- Also there were problems like joining statements, password encryption. We were able to solve it by learning how and when to use the joining statements. These joining statements are used to join two tables in the database. We learn how to implement encryption techniques in our project. These techniques are used to provide security in our project.
 
**Hibernate:**

- The main challenges were faced during the creation of JPA annotations, like how to use these annotations and where to use it in the code. We solved this problem by learning how to implement these annotations and when and where are they required. By using annotations like @Entity, @Id, @Column etc. we created tables in database.
- Another issue faced was working on HTTP Servlet Request and Response methods like how to take inputs from the client on the browser and how to give response to the client. We solved it by learning the methods of HTTP Servlets like ‘getParameter’ method and another methods. These methods are used to take request and response from the browser.
- We also faced problems like while connecting a Spring Boot project to the database using JPA/Hibernate. We solved it using mapping techniques in the project. Further by learning the use of ORM tool called Hibernate. It is a ORM (Object Relational Mapping) tool which is used to connect to a database. Before JPA, ORM was the term more used to refer these frameworks

**Spring Boot:**

We faced several challenges while working with Spring Boot application. Those Challenges are:
- Main problem we faced while project development was implementing Restful Web Services. We learned how and where to use these services and implemented Mapping Methods and solved the problem. To configure the mapping of web requests we used the @RequestMapping annotation. This could be applied on class-level or method-level in a controller.
- Another challenge we faced was working with Micro services and establishing a connection with database. We had a hard time establishing connection with the database and executing CRUD operations in micro servers. We were able to solve it by learning properties and methods required to establish the connection with database and also, how and where to use these properties to make execute CRUD operations.
 
Spring:

Working with Spring MVC took the most of our time, but we were finally able to solve the challenges faced, which are as followed:
- Scalability: MVC doesn't guarantee scalability. Since, we couldn't scale the parts realated to performance. To solve this issue the whole application needs to be scaled.
- Testability: The testability of the application is not straightforward when using MVC. Although it's possible to test each component independently, it's needed to integrate all the parts before we can test one functionality end to end.
- Another problem that we faced during project implementation was linking the JSP files to controller classes. We overcome this problem by learning how to give connection to individual JSP files and also JSP pages to a controller class. The proper connection helped our project to execute properly.
