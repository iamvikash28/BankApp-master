# BankApp-master

A full-featured **Banking Application** built with **Java Spring Boot**, demonstrating secure account management, customer handling, and transaction processing.  
This project is designed as a coding exercise but follows real-world architecture patterns used in enterprise applications.

---

## 📸 Preview

<img width="1920" height="1048" alt="screencapture-localhost-8989-bank-api-swagger-ui-html-2026-04-17-13_41_51" src="https://github.com/user-attachments/assets/83f35131-fc22-4d25-8f6d-30a01f2ce3f0" />

<img width="1920" height="2926" alt="screencapture-localhost-8989-bank-api-swagger-ui-html-2026-04-17-13_42_45" src="https://github.com/user-attachments/assets/495756a9-10e9-4e41-864a-cb3fa138cc85" />

---

## 📌 Features
- **Customer Management**  
  - Create, update, and view customer details  
  - Manage addresses, contact information, and linked accounts
- **Account Management**  
  - Create and manage bank accounts  
  - View account balances and details
- **Transactions**  
  - Transfer money between accounts  
  - View transaction history
- **Security**  
  - Spring Security configuration for authentication and authorization
- **Clean Architecture**  
  - Separation of concerns with `controller`, `domain`, `model`, `repository`, and `config` layers

---

## 🏗 Project Structure
src/main/java/com/coding/exercise/bankapp/
│
├── config/ # Application & Security configuration
├── controller/ # REST API endpoints for accounts & customers
├── domain/ # Domain objects for request/response payloads
├── model/ # Entity classes mapped to the database
├── repository/ # Spring Data JPA repositories
└── BankingApplication.java # Main entry point

---

## 🚀 Getting Started

### Prerequisites
- **Java 17+**
- **Maven 3+**
- (Optional) **MySQL/PostgreSQL** if you want a persistent DB setup

### Installation & Run
```bash
# Clone the repository
git clone https://github.com/iamvikash28/BankApp.git
```
```bash
# Navigate into the project
cd BankApp
```
```bash
# Build the project
mvn clean install
```
```bash
# Run the application
mvn spring-boot:run
```

## 🔗 API Endpoints (Example)
| Method | Endpoint                 | Description         |
| ------ | ------------------------ | ------------------- |
| `POST` | `/customers`             | Create new customer |
| `GET`  | `/customers/{id}`        | Get customer by ID  |
| `POST` | `/accounts`              | Create new account  |
| `POST` | `/transactions/transfer` | Transfer funds      |


## 🛠 Technologies Used

- **Java Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **Maven**
- **REST API**
- **H2/MySQL Database**

--- 

## 👤 Author

**Vikash Verma**
Aspiring Data Analyst | Excel · SQL · Power BI · Python | E-mail- vikashverma566@gmail.com

---
