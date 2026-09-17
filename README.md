# OIBSIP

## Oasis Infobyte Java Development Internship

### Task 1: Online Reservation System

This project is developed as part of the Oasis Infobyte Java Development Internship.

## Project Description

The Online Reservation System is a Java-based desktop application that allows users to log in, book train tickets, and cancel reservations using a MySQL database.

## Technologies Used

- Java
- Swing
- JDBC
- MySQL
- IntelliJ IDEA
- Maven

## Features

- User login authentication
- Train selection
- Ticket booking
- Automatic PNR generation
- Journey date entry
- Source and destination station details
- Ticket cancellation using PNR
- MySQL database connectivity
- Input validation

## Screenshots

### Login Screen
![Login Screen](screenshots/login.jpg)

### Main Menu
![Main Menu](screenshots/main-menu.jpg)

### Book Ticket
![Book Ticket](screenshots/booking-form.jpg)

### Booking Successful
![Booking Successful](screenshots/booking-success.jpg)

### Cancel Ticket
![Cancel Ticket](screenshots/cancellation-form.jpg)

### Cancellation Successful
![Cancellation Successful](screenshots/cancellation-success.jpg)
Internship

How to Run
Install Java JDK.
Install MySQL.
Create the OnlineReservationSystem database.
Create the required tables.
Update the MySQL username and password in DBConnection.java.
Open the project in IntelliJ IDEA.
Run LoginForm.java.


Login using the provided credentials.

Username: admin
Password: admin123

OnlineReservationSystem/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── org/
                └── example/
                    ├── DBConnection.java
                    ├── LoginForm.java
                    ├── MainMenu.java
                    ├── ReservationForm.java
                    └── CancellationForm.java


## Database Tables

- `users`
- `trains`
- `reservations`

This project is completed as part of the Oasis Infobyte Java Development Internship.

#oasisinfobyte


Project Overview
ATM Interface is a console-based Java application that simulates basic ATM operations.

The project demonstrates Object-Oriented Programming (OOP), authentication, account management, transactions, and collection handling using Java.

Objective
The main objective of this project is to develop a simple ATM system where users can securely log in using their User ID and PIN and perform basic banking operations.

Technologies Used
Java
Object-Oriented Programming (OOP)
ArrayList
HashMap
IntelliJ IDEA
JDK 24
Features
User ID and PIN authentication
Maximum 3 login attempts
Check account balance
Deposit money
Withdraw money
Transfer money between accounts
Insufficient funds validation
Transaction history
Invalid input handling
Exit/Quit option
Sample Login Credentials
Account 1
User ID: Aashish
PIN: 1234
Account ID: ACC001
Initial Balance: ₹10,000
Account 2
User ID: Rahul
PIN: 5678
Account ID: ACC002
Initial Balance: ₹8,000
Project Structure
ATMInterface
│
├── src
│   ├── Main.java
│   ├── ATM.java
│   ├── Account.java
│   ├── Transaction.java
│   └── Bank.java
│
└── README.md



Class Description

Main.java
Starts the ATM application by creating the Bank and ATM objects.

ATM.java
Controls the ATM operations such as login, menu, deposit, withdrawal, transfer, balance checking, and transaction history.

Account.java
Stores account information such as Account ID, User ID, PIN, and balance.

Transaction.java
Represents a banking transaction and stores transaction details.

Bank.java
Manages accounts, authentication, and money transfers between accounts.

Application Flow
Start the application.
Enter User ID and PIN.
User gets maximum 3 login attempts.
After successful login, the ATM main menu is displayed.
User can check balance, deposit, withdraw, transfer money, or view transaction history.
The application validates transactions and prevents invalid operations.
User can quit the application.
Validation

The application handles:

Incorrect User ID or PIN
Maximum login attempts
Invalid numeric input
Negative or zero transaction amounts
Insufficient account balance
Transfer to the same account
Invalid recipient Account ID
Learning Outcomes

Through this project, I learned:

Java OOP concepts
Classes and objects
Encapsulation
Constructors and methods
ArrayList and HashMap
Exception handling
User input handling using Scanner
Basic banking transaction logic
Input validation
Future Improvements
MySQL database integration
GUI-based ATM interface
PIN change functionality
Transaction date and time
Receipt generation
Secure password/PIN storage
Multiple user session support
Author

Aashish Borde

Oasis Infobyte Java Development Internship

Task 3 - ATM Interface

