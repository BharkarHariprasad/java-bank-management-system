# 🏦 Bank Management System (Console-Based Application)

## Project Title

Bank Management System – Console-Based Core Java Application

---

## Overview

The Bank Management System is a console-based application developed using Core Java to simulate basic banking operations. The system allows users to create accounts, perform deposits and withdrawals, and track transactions through a structured class-based design.

This project was developed as a team-based academic project during the early stage of learning Core Java. I contributed to the overall system design and class structure planning before distributing modules across team members for implementation.

The application models real-world banking operations using object-oriented programming principles such as abstraction, encapsulation, inheritance, and polymorphism.

---

## Features

- Account creation and management
- Deposit and withdrawal operations
- Balance management
- Transaction tracking
- Multiple account types (Saving, Current, Salary)
- Loan account types (Personal Loan, Business Loan)
- Basic employee and user system interaction
- Console-based menu-driven interface

---

## Technologies

Core Java | Object-Oriented Programming | Console-Based Application

---

## Architecture

The application follows a modular structure separating different responsibilities into packages.

```
User Interaction (Console)
        ↓
Bank System Controller
        ↓
Account Management
        ↓
Transaction Processing
        ↓
Reports & Notifications
```

The system is organized into three main modules:

- **account package** → Account types and account operations  
- **bank package** → System entry point, authentication, employee management  
- **transaction package** → Transaction handling, reports, and notifications

---

## Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Enum usage for transaction types
- Modular class design
- Logical flow design for banking operations

---

## Project Structure

```
BankManagementSystem
│
└── src
    │
    ├── account
    │   ├── BankAccount.java
    │   ├── SavingAccount.java
    │   ├── CurrentAccount.java
    │   ├── SalaryAccount.java
    │   ├── LoanAccount.java
    │   ├── PersonalLoan.java
    │   └── BusinessLoan.java
    │
    ├── bank
    │   ├── Bank.java
    │   ├── BankEmployee.java
    │   ├── BankEmployeesDetails.java
    │   ├── Designation.java
    │   ├── HomePage.java
    │   ├── Login.java
    │   └── User.java
    │
    └── transaction
        ├── Transaction.java
        ├── TransactionType.java
        ├── Notification.java
        └── Reports.java
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/BharkarHariprasad/java-bank-management-system.git
```

2. Open the project in **Eclipse IDE** or any Java IDE.

3. Navigate to the main class:

```
Login.java
```

4. Run the program as a **Java Application**.

5. Login using one of the default credentials below.

---

## Default Login Credentials

The system implements a simple **role-based authentication system**.

| Role | Employee ID | Password | Access |
|-----|-------------|----------|-------|
| Manager | 201 | neha@123 | Full access to all banking operations |
| Employee | 202 | ramesh@456 | Limited access to customer account operations |

### Manager Permissions
- View all accounts
- Manage employees
- Generate reports
- Monitor transactions
- Full administrative access

### Employee Permissions
- Create customer accounts
- Deposit and withdraw funds
- View account details
- Process basic banking transactions

---

## Learning Context

This project was developed during the initial stage of learning Core Java and helped strengthen understanding of object-oriented programming principles and modular class design.

It also provided practical experience in structuring a console-based system and collaborating within a small development team.

---

## Author

**Hariprasad Bharkar**  
Java Backend Developer  

GitHub: [BharkarHariprasad](https://github.com/BharkarHariprasad)  
LinkedIn: [Hariprasad Bharkar](https://www.linkedin.com/in/your-linkedin-profile)
