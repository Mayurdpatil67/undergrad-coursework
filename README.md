# Online Banking System

## Introduction
The **Online Banking System** is a Java-based web application designed to provide users with a secure and convenient platform for online banking transactions. It includes features for account management, fund transfers, transaction history, and security measures to protect user information.

## Objectives
- Develop a web-based application for online banking using Java.
- Implement secure user authentication and authorization.
- Provide functionalities for account management, fund transfers, and transaction history.
- Utilize MySQL for database storage and management.
- Implement encryption and other security measures to protect sensitive user data.

## Technologies Used
- **Java** (Programming language)
- **MySQL** (Relational database)
- **JavaServer Pages (JSP)** for frontend
- **Servlets** for backend
- **HTML, CSS, JavaScript** (Frontend)
- **JDBC** (Java Database Connectivity) for database interaction

## Features
### User Authentication
- Secure login and registration functionalities.
- Password encryption for enhanced security.

### Account Management
- View account details, including balance and transaction history.
- Update account information.

### Fund Transfers
- Transfer funds between accounts.
- Display transaction receipts and updates on account balances.

### Transaction History
- Maintain a detailed transaction history for each account.
- Display transaction details, including date, type (deposit, withdrawal, transfer), and amount.

### Security Measures
- Secure practices such as password hashing, HTTPS, and session management.

## Project Structure
```
com.bank.controller  # Contains servlets for handling user requests
com.bank.model       # JavaBeans representing entities like User, Account, and Transaction
com.bank.dao         # Data Access Objects for database interactions
com.bank.util        # Utility classes for encryption and other functionalities
```

## User Interface Design
### Web Pages
- **Login and Registration Forms**
- **Account Dashboard** displaying balance, transaction history, and fund transfer options.

## Database Design
### Schema
#### Users Table
```
user_id (Primary Key)
username
password_hash
email
```
#### Accounts Table
```
account_id (Primary Key)
user_id (Foreign Key)
balance
```
#### Transactions Table
```
transaction_id (Primary Key)
account_id (Foreign Key)
type
amount
date
```

## Conclusion
This project provides a secure and efficient online banking system with essential functionalities for users. It showcases secure authentication, financial transactions, and database interactions using Java and MySQL.

## Installation and Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/online-banking-system.git
   ```
2. Import the project into your preferred IDE.
3. Configure the **MySQL database** and update connection details in the DAO classes.
4. Deploy the application on a Tomcat server.
5. Access the application via `http://localhost:8080/OnlineBankingSystem`.
