## Expense-Tracker-backend
This is only the backend of  Expense Tracker which allows users add, update, and delete expenses, view expense reports.  It is built using Spring Boot with PostgreSQL.

## Features
Expense Tracking: Add, view, update and delete expenses.

## Technologies Used
- Backend: Spring Boot
- Database: PostgreSQL

## Installation

## Prerequisites
- Java: Ensure Java is installed for running Spring Boot. You can download it from java.com.
- PostgreSQL: Ensure PostgreSQL is installed and running. You can download it from postgresql.org.
- ORM: Spring Data JPA (Hibernate)
- Testing: Spring Boot Test (JUnit)

## Backend

1. Navigate to the backend directory:
```
cd Expense-Tracker/backend
```
2.Configure the application.properties file with your PostgreSQL database credentials.
3.Build and run the Spring Boot application:
```
./mvnw spring-boot:run
```
The backend will be available at http://localhost:8080.

## Usage
-  Add an Expense: Add new expenses, including the date, amount, and description.

- Update an Expense: To update its details.

- Delete an Expense: To remove it.

