# SmartCareWebApplication
Virtual Web Application for a hospital

###Web Application for a hospital

##Task

Build a web application for a hospital that allows the patients, doctors, nurses and admins to login with their emails and password for performing a specific task.

##Summary

This application was built using Netbeans with JAVA EE. Netbeans comes with JAVA programming language which allows me to implement the back-end of the application based on the principle of object oriented programming such as treating each patient, admin and doctor as objects and each functionality as a method within the class. For front-end of the application, this was implementd by creating jsp files with the use of html, javascripts and css for styling and implementing the web interface. The database for this project was created by using the service of the Netbeans.

##Functionality

This application simulates the web application for a hospital in which patients can register or login with their surname and date of birth then they can book an appointment, find the nearest hosipitals near them on the map, pay invoices or request for re-issue invoices. For doctors, they can see the appointments schedule, find patient details or issue a prescription. For nurses, they can only see the appointments schedule. Lastly, for admins, they can issue an invoice, manage the appointments, find patient details, produce weekly documents, register new staff accounts and manage the prices of surgery and consulation.    

##Design

The design of this application followed the pattern of MVC such that it has interface that was developed by using jsp files with the use of html, css and javascripts for the view part. For the controller part, this was implemented with the use of servlets which handles the interactions between the interface, model and database. For the model part, this was alll designed to be used JAVA for developing with the principle of object oriented programming such that everything is treated as an object which can be created as a class.

##Run Locally

- Clone the folder AppointmentSystem
- Make sure to install Netbeans
- Run the jar file \AppointmentSystem\PatientMakeAppointmentPrototype.jar
- You can login with username and password in the document \AppointmentSystem\How to Run the Prototype.docx   
- Optionally, the application can be run by using Netbeans then run the file \AppointmentSystem\src\hospmansys\controllers_and_fxml\AppointmentSystem.JAVA
- Further details on how to run the application can be found in the How to Run the Prototype document 

##Tech Stack

- Netbeans
- JAVA
- SceneBuilder

