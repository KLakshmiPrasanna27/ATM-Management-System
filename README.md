# 🏧 ATM Management System

## 📌 Overview

The ATM Management System is a Java-based desktop application that simulates the functionality of an Automated Teller Machine (ATM). It provides users with a secure and interactive interface to perform essential banking operations such as account creation, deposits, withdrawals, balance inquiries, mini statements, and PIN changes.

The project is built using Java Swing and AWT for the graphical user interface and MySQL for database management. It demonstrates the implementation of object-oriented programming concepts, database connectivity, event handling, and user authentication.

---

## 🚀 Features

* User Registration and Account Creation
* Secure User Authentication
* Cash Deposit
* Cash Withdrawal
* Balance Inquiry
* Mini Statement Generation
* Fast Cash Transactions
* PIN Change Facility
* Transaction History Management
* MySQL Database Integration
* User-Friendly Graphical Interface

---

## 🛠️ Technologies Used

| Technology | Purpose                    |
| ---------- | -------------------------- |
| Java       | Core Programming Language  |
| Swing      | GUI Development            |
| AWT        | GUI Components             |
| JDBC       | Database Connectivity      |
| MySQL      | Database Management System |

---

## 📂 Project Structure

```text
ATM-Management-System/
│
├── src/
│   ├── Login.java
│   ├── Signup.java
│   ├── Deposit.java
│   ├── Withdraw.java
│   ├── BalanceEnquiry.java
│   ├── MiniStatement.java
│   ├── FastCash.java
│   ├── PinChange.java
│   └── Conn.java
│
├── database/
│   └── atm_management.sql
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Java JDK 8 or above
* MySQL Server
* MySQL Workbench (Optional)
* Eclipse IDE / IntelliJ IDEA / VS Code

### Steps to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/ATM-Management-System.git
```

2. Open the project in your preferred Java IDE.

3. Create a MySQL database:

```sql
CREATE DATABASE bankmanagementsystem;
```

4. Import the SQL tables required for the project.

5. Update database credentials in the JDBC connection file:

```java
String url = "jdbc:mysql://localhost:3306/bankmanagementsystem";
String username = "root";
String password = "your_password";
```

6. Run the Login.java file to start the application.

---

## 🖥️ Functional Modules

### 1. Account Registration

* Create a new user account.
* Store user information securely in the database.

### 2. Login Authentication

* Validate user credentials.
* Allow access to banking services.

### 3. Deposit

* Add funds to the account.
* Update account balance automatically.

### 4. Withdrawal

* Withdraw available funds.
* Prevent invalid transactions.

### 5. Balance Inquiry

* Display the current account balance.

### 6. Mini Statement

* Show recent transaction history.

### 7. Fast Cash

* Quick withdrawal using predefined amounts.

### 8. PIN Change

* Allow users to update their ATM PIN securely.

---

## 🎯 Learning Outcomes

Through this project, the following concepts are implemented:

* Object-Oriented Programming (OOP)
* Java Swing GUI Development
* Event Handling
* JDBC Connectivity
* Database Design and Management
* Authentication and Validation
* Transaction Processing

---

## 📸 Screenshots

Add screenshots of the following pages:

* Login Page
* Signup Page
* Main Menu
* Deposit Screen
* Withdrawal Screen
* Mini Statement
* Balance Inquiry

---

## 🔮 Future Enhancements

* Password Encryption
* Online Banking Integration
* Fund Transfer Between Accounts
* Email/SMS Notifications
* User Profile Management
* Admin Dashboard
* Transaction Analytics

---

## 👩‍💻 Author

**Kasarla Lakshmi Prasanna**

* GitHub: https://github.com/KLakshmiPrasanna27
* LinkedIn: https://linkedin.com/in/lakshmi-prasanna-reddy-81b1502a4

---

## 📄 License

This project is developed for educational and learning purposes.
