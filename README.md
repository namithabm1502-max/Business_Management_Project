# Business Management Web Application : <br>


<img width="1920" height="1080" alt="Screenshot 2026-07-22 014844" src="https://github.com/user-attachments/assets/5061d6ae-3ba5-4038-a710-932a5c2fae8f" />





## Project Desc : Business Management Web Application 
  => The Business Management Web Application is a comprehensive tool designed to help businesses manage various aspects of their operations. 
          It provides a user-friendly interface for tasks like managing customer data, inventory, orders, and more.



## Features  :

- **Customer Management**: Easily add, update, and delete customer information.
- **Inventory Management**: Keep track of your inventory items, including stock levels and pricing.
- **Order Management**: Manage customer orders such as order creation .
- **User Authentication**: Secure login and authentication for admin and staff members.
- **Role-Based Access Control**: Define roles and permissions for different user types.
- **Thymeleaf Templates**: Utilizes Thymeleaf for dynamic HTML templates.
- **Database Integration**: Integrated with MySQL for data storage.




## Technologies Used :

- Spring Boot: Backend framework for building Java-based web applications.
- Thymeleaf: Server-side Java template engine for dynamic HTML generation.
- MySQL: Relational database management system for data storage.
- IDE/Tool : Spring Tool Suite 4 (Eclipse)




## Installation :

1. Clone the repository : $ git clone https://github.com/SuhasKamate/Business_Management_Project.git <br>

2. Import the project inside STS/Eclipse : <br>
     - Open STS/Eclipse > file > import > maven > existing project > browse > finish . <br>
     
3. Make sure you are in the Business_Management_Project directory. <br>

![packageExplorer](https://github.com/SuhasKamate/Business_Management_Project/assets/126138738/3ea1eb7f-8e49-4b76-96e4-798b6b8e8715)


4.Configure the database connection is application.properties (check the Database section for more information). <br>

5.Run the project (by running main method is BusinessProjectApplication.java) OR right clink on the project > Run As > Spring Boot App. <br>

6.Open http://localhost:2330/home in any browser. <br>

7.Now your tables will be created in the databse. <br>
   - You have to add one admin data manually to login as admin, So add one admin data. <br>
    



## Database :

MySQL can be used as the database for this project. 
The database connection can be configured in the application.properties file, with the appropriate values for the following properties: <br>

spring.datasource.name=[Your Database Name] <br>
spring.datasource.url=jdbc:mysql://localhost:3306/[Your Database Name] <br>
spring.datasource.password=[Your password] <br>
spring.datasource.username=[Your username] <br>
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver <br>
spring.jpa.hibernate.ddl-auto=update <br>
server.port=2330[Optional] <br>




## WorkFlow :

![workflow](https://github.com/SuhasKamate/Business_Management_Project/assets/126138738/aea72470-49c8-41a4-8974-48737638ae19)





## Preview :


#### Products 

<img width="1920" height="1080" alt="Screenshot 2026-07-22 014858" src="https://github.com/user-attachments/assets/7f4c8450-e1f2-45c3-864e-46a200fa19fe" />



#### Location 

<img width="1920" height="1080" alt="Screenshot 2026-07-22 014915" src="https://github.com/user-attachments/assets/d7ef296f-9115-4d15-b1c9-975bc5d3c52f" />




#### Log

<img width="1920" height="1080" alt="Screenshot 2026-07-22 014939" src="https://github.com/user-attachments/assets/a8d04980-2cf8-485e-9b24-d30b3b467e60" />



#### AdminPanel

![adminpanel](https://github.com/SuhasKamate/Business_Management_Project/assets/126138738/b89aa5ee-3f7f-4145-b063-048729e7fbe9)


### About

<img width="1920" height="1080" alt="Screenshot 2026-07-22 014929" src="https://github.com/user-attachments/assets/98e8a41a-f482-472e-9d3b-394797e3bf36" />



#### UserPanel 

<img width="1920" height="1080" alt="Screenshot 2026-07-22 020644" src="https://github.com/user-attachments/assets/16dae374-19d1-486d-933f-6295346d5a74" />



### Exception page

<img width="1920" height="1080" alt="Screenshot 2026-07-22 021031" src="https://github.com/user-attachments/assets/0eb7c89a-8dfd-451f-a29f-64ae694b73aa" />




