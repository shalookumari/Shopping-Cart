**About**


This is a full-stack Online Shop web application for practicing Spring Boot 4 and Hibernate 5. The idea was to build some basic shopping cart web app for grocery Shopping.
There is a login and registration functionality included.
Users can shop for products. Each user has his own shopping cart which include session functionality. 


**Prerequisites**


- Java
- Maven 
- MySQL
- Spring Boot
- Hibernate
- HTML , CSS & Javascript
- JPA


**Configuration Files**


Folder src/resources, contains config files for Shopping Cart Spring Boot application.
- src/resources/application.propeties
- main configuration file. One can change username and password here along with port number.


**Features**

- Registration: User will enter details like First and Last name, Email Id, Password, Contact number and Date of Birth and register themself.
- Login: User will login themselves using Email and Password which they registered themselves with.
- Home Page: This page has links to Add Customer, Items or Log THemselves out of the applictaion.
- Add Customer: Admin can add customers by filling in customer's name and Contact details.
- Items (Include Add items, Update items, Items Instock, Delete Selected Items)
- Customer: Customer can Shop watches, Check Items in stock, Update stock and deleted selecteed items.
- Bill: Customer can add Item name, Price and Quantity.
- Payment: After Bill generation, customer can fill in Shipping Address and Card Details.

**Guidelines To Run Project:**


- Download the project and open in Eclipse JAVA EE. 
- Need JRE 1.8 or above. 
- Configure Build Path
- If it opens up as JAVA projects, Right-click the project and select Configure > Convert to Maven Project. Complete the Maven POM dialog. Click Finish to complete the dialog. Update the project.
- Go to "application.properties" file and replace MySQL url, username and password bean properties with host computer`s MySQL url, username and password.
- Run the provided SQL script to get the database with populated values on host machine. 
- Update the pom.xml and maven dependencies to download all the required libraries. 
- Run the project, select Run as Spring Boot app.

Note: The backend API url is configured in src/environments/environment.ts of the frontend project. It is localhost:8080 by default.

**Folder Structure**

- design
    - Behavioural Diagrams
    - Structural Diagrams
- src
    - main
        - java/com/ltts
            - shoppingcart/Entity
            - shopping
                - config
                - model
                - pagination
                - repository
                - service
                - web
        - resources
            - static
            - templates
            - application.properties
    - test
- target
    - classes
        - META-INF
        - com/ltts
        - static
        - templates
        - application.properties
- pom.xml

## System Level Diagram

![System Level Diagram](https://github.com/PS99003587/Team-2-Shopping-Cart-Project/blob/main/Team_2_ShoppingCart_Final/design/System%20Level%20Design.png)
