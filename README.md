# Cafe-management-system
Cafe Management System

A full-stack Cafe Management System developed using Java for the backend and Angular for the frontend. This system allows the management of cafe operations such as managing menu items, orders, customer details, and more.

**Features**
Customer Management: Add, update, and view customer details.
Menu Management: Manage food and drink items, including prices and availability.
Order Management: Process customer orders and track their status.
Billing: Generate bills for customers.
Admin Interface: Admin can add/edit menu items, view orders, and manage customer data.
Tech Stack

Frontend: Angular
Backend: Java (Spring Boot)
Database: MySQL
Other: Maven (for Java dependencies), npm (for Angular dependencies)
Requirements

Java 8 or later
Node.js (for frontend)
MySQL (for database)
Maven (for Java backend build)




Installation

Clone the repository:
git clone https://github.com/kishanharale/Cafe-management-system.git

Set up the backend:
Navigate to the backend directory:
cd backend

Install dependencies and build the project using Maven:
mvn install

Run the backend application:
mvn spring-boot:run

Set up the frontend:
Navigate to the frontend directory:
cd frontend

Install frontend dependencies:
npm install

Run the frontend application:
ng serve

Database Setup:
Install and set up MySQL if you haven't already.

Create a new database:
CREATE DATABASE cafe_management_system;
Update application.properties in the backend directory with your MySQL database details:
spring.datasource.url=jdbc:mysql://localhost:3306/cafe_management_system
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

Usage
Frontend: Open your browser and go to http://localhost:4200 to access the Cafe Management System interface.
Backend: The backend API is available at http://localhost:8080. It provides RESTful endpoints to manage customers, orders, and menu items.

Testing
Backend testing:
mvn test

Frontend testing:
ng test

Contributing
Fork the repository.
Create your feature branch:
git checkout -b feature-name
Commit your changes:
git commit -am 'Add feature'
Push to your branch:
git push origin feature-name
Open a pull request.
