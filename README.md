## SaveHer – Emergency Safety App Backend

This is a Spring Boot project for SaveHer, a safety application that allows users to register, manage emergency contacts, and send SOS alerts.

## 📦 Features
User registration and login

Add, view, and delete emergency contacts

Trigger SOS alerts with location

RESTful API with Spring Boot

MySQL database integration

Maven-based project


## 🛠 Technologies Used

- Java
- Spring Boot
- Maven
- Spring Web
- JPA 
- MySQL 

## 📁 Project Structure
src/main/java/com/saveher/
    SaveHerApplication.java
    model/
        User.java
        Contact.java
        SOSRequest.java
    repository/
        UserRepository.java
        ContactRepository.java
    service/
        UserService.java
        ContactService.java
        SOSService.java
    controller/
        UserController.java
        ContactController.java
        SOSController.java
resources/
    application.properties
pom.xml
README.md


.
├── src/
│ └── main/
│ └── java/
│ └── com/
│ └── yourpackage/
│ └── product/ <- Core logic
├── .mvn/
├── pom.xml
└── README.md

## How to Run

1> Clone the repository:

git clone https://github.com/chayabr/SaveHer.git
cd SaveHer


2> Configure MySQL in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/saveherdb
spring.datasource.username=root
spring.datasource.password=chaya@1234

3>Build the project:

mvn clean install


4>Run the application:

mvn spring-boot:run


5>Access the app at:

http://localhost:8080


📬 API Endpoints
User
Method	Endpoint	Description
POST	/users/register	Register a new user
POST	/users/login	User login

Contacts
Method	Endpoint	Description
GET	/contacts/{userId}	Get all contacts for a user
POST	/contacts	Add a new contact
DELETE	/contacts/{id}	Delete a contact by ID

SOS
Method	Endpoint	Description
POST	/sos/send	Trigger SOS alert

🧑‍💻 Author
Chaya B R




