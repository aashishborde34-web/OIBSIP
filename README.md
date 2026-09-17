# OIBSIP

## Oasis Infobyte Java Development Internship

This repository contains the projects completed as part of the **Oasis Infobyte Java Development Internship**.

---

# Task 1: Online Reservation System

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

[Login Screen](https://aashishborde34-web.github.io/OIBSIP/screenshots/login.jpg)

### Main Menu

[Main Menu](https://aashishborde34-web.github.io/OIBSIP/screenshots/main-menu.jpg)

### Book Ticket

[Book Ticket](https://aashishborde34-web.github.io/OIBSIP/screenshots/booking-form.jpg)

### Booking Successful

[Booking Successful](https://aashishborde34-web.github.io/OIBSIP/screenshots/booking-success.jpg)

### Cancel Ticket

[Cancel Ticket](https://aashishborde34-web.github.io/OIBSIP/screenshots/cancellation-form.jpg)

### Cancellation Successful

[Cancellation Successful](https://aashishborde34-web.github.io/OIBSIP/screenshots/cancellation-success.jpg)

## How to Run

1. Install Java JDK.
2. Install MySQL.
3. Create the `OnlineReservationSystem` database.
4. Create the required tables.
5. Update the MySQL username and password in `DBConnection.java`.
6. Open the project in IntelliJ IDEA.
7. Run `LoginForm.java`.
8. Login using the provided credentials.

### Login Credentials

**Username:** `admin`  
**Password:** `admin123`

## Project Structure

```text
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
