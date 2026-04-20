# Banking Application

A RESTful Banking Application developed using Spring Boot and MySQL that allows users to manage bank accounts and perform basic transactions such as account creation, retrieval, and deposit operations.

---

## Features
- Create a new bank account
- Retrieve account details by ID
- Deposit money into an account
- Layered architecture (Controller → Service → Repository → DTO)
- Clean code structure with DTO mapping

---

## Tech Stack
- Java 21
- Spring Boot
- Spring Data JPA (Hibernate)
- MySQL
- Maven

---

## API Endpoints

### ➤ Create Account
**POST** `/api/accounts`

Request Body:
```json
{
  "accountHolderName": "John Doe",
  "balance": 1000
}
