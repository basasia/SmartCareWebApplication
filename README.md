# SmartCareWebApplication
Virtual Web Application for a hospital develop by using JAVA, html and css.

###Web Application for a hospital

##Task

Build a web application for a hospital that allows the patients, doctors, nurses and admins to login with their emails and password for performing a specific task.

##Summary

This application was built using Netbeans with JAVA EE. Netbeans comes with JAVA programming language which allows me to implement the back-end of the application based on the principle of object oriented programming such as treating each patient, admin and doctor as objects and each functionality as a method within the class. For front-end of the application, this was implementd by creating jsp files with the use of html and css for styling and implementing the web interface. The database for this project was created by using the service of the Netbeans.

##Functionality

This application simulates the web application for a hospital in which patients can register or login with their surname and date of birth then they can book an appointment, find the nearest hosipitals near them on the map, pay invoices or request for re-issue invoices. For doctors, they can see the appointments schedule, find patient details or issue a prescription. For nurses, they can only see the appointments schedule. Lastly, for admins, they can issue an invoice, manage the appointments, find patient details, produce weekly documents, register new staff accounts and manage the prices of surgery and consulation.    

##Design

The design of this application followed the pattern of MVC such that it has interface that was developed by using jsp files with the use of html, css and javascripts for the view part. For the controller part, this was implemented with the use of servlets which handles the interactions between the interface, model and database. For the model part, this was alll designed to be used JAVA for developing with the principle of object oriented programming such that everything is treated as an object which can be created as a class.

##Run Locally

- Clone the folder SmartCareWebApplication
- Make sure to install Netbeans
- Create a database name: "SMARTCARE", user: "SmartCare", password: "HSVu2G".
- Start the database sever
- Connect to the database that just created
- Execute all the commands in the \SmartCareWebApplication\SQL to create all the tables needed.
- Intialize the admin account within the database as this account cannot be registered through the web application.    
- Run the file \SmartCare\src\java\smartcare\controllers\Login.JAVA  to start the web application.
- You can login with the existing account or register a new one as a patient. Once registered, the password will be as day-month-year. For example, the date of birth is 02-06-2021, the password will be 020621. To register new accounts for docters and nurses, this need to be created via the admin account.   

##Tech Stack

- Netbeans
- JAVA
- JAVA EE


Login page:

![image](https://user-images.githubusercontent.com/60352487/120791964-0d432000-c55f-11eb-9caf-3f3f703f11ba.png)

Admin page:

![image](https://user-images.githubusercontent.com/60352487/120792110-3cf22800-c55f-11eb-8d8f-53d08880eb0b.png)

Doctor page:

![image](https://user-images.githubusercontent.com/60352487/120792205-55fad900-c55f-11eb-9d68-208a7136347f.png)

Nurse page:

![image](https://user-images.githubusercontent.com/60352487/120792698-1e406100-c560-11eb-9271-fe4f2cb59b5a.png)




