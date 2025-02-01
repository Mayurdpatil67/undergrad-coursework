# Bank Management System

This is a **Bank Management System** built in Java. It allows users to manage bank accounts, perform transactions, and view account details. The system is designed to simulate typical banking operations such as account creation, withdrawal, deposit, and balance checking. It serves as a demonstration of object-oriented programming concepts and Java GUI development.

## Features

- **Account Creation**: Allows customers to create new accounts by providing basic details like name, address, phone number, and initial deposit.
- **Deposit Money**: Users can deposit money into their accounts, updating the balance accordingly.
- **Withdraw Money**: Allows users to withdraw money from their accounts, ensuring that there is sufficient balance.
- **Account Information**: Users can view their account details such as balance, transaction history, and personal information.
- **Transaction History**: Keeps track of all deposits and withdrawals made in the account.
- **Admin Panel**: Admin users can manage multiple customer accounts and perform administrative tasks like viewing all accounts, deleting accounts, or making updates to account details.

## Technologies Used

- **Java**: The core programming language used for the development of the application.
- **Swing**: A GUI toolkit used for building the graphical interface of the system.
- **JDBC (Java Database Connectivity)**: Used for connecting to a database to persist user data and transaction history.
- **MySQL**: A relational database used to store customer information, transaction history, and account data.

## Prerequisites

To run this project on your local machine, you will need the following:

- **Java** (JDK 8 or higher)
- **MySQL** (for database management)
- **JDBC driver** (for database connection)

## Installation

### Clone the Repository

```bash
git clone https://github.com/Mayurdpatil67/academics-ug.git
cd bank-management-system
```

### Set Up MySQL Database

1. Create a database called `bank_management` and import the SQL schema for creating tables such as accounts, transactions, and users.
2. A sample SQL file (`db_setup.sql`) is included in the repository.

### Configure Database Connection

Edit the `DatabaseConnection.java` file to configure your MySQL connection parameters (e.g., username, password, and database name).

### Run the Application

1. Open the project in your preferred IDE (such as IntelliJ IDEA, Eclipse, or NetBeans).
2. Compile and run the `BankManagementSystem.java` file.

## Example Usage

Once the application is running, you will be presented with a login screen. You can choose to log in as an **Admin** or **Customer**.

### Admin Panel

As an admin, you can:

- Add or delete accounts.
- View all accounts in the bank.
- Manage customer transactions.

### Customer Panel

As a customer, you can:

- Create a new account.
- Deposit or withdraw money.
- View account details and transaction history.
