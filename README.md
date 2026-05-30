# Secure Login System

## Overview

The Secure Login System is a cybersecurity-focused web application developed using Python, Flask, SQLite, and bcrypt. The project demonstrates secure user authentication practices by implementing user registration, password hashing, login authentication, session management, and logout functionality.

This project is designed to provide a secure method for managing user accounts while protecting sensitive information such as passwords.

---

## Features

* User Registration
* Secure User Login
* Password Hashing using bcrypt
* SQLite Database Integration
* Session Management
* User Logout Functionality
* SQL Injection Protection using Parameterized Queries
* Secure Password Storage
* Simple and User-Friendly Interface

---

## Technologies Used

* Python
* Flask
* SQLite
* bcrypt
* HTML
* CSS

---

## Project Structure

Secure_Login_System/

├── app.py

├── users.db

├── templates/

│ ├── register.html

│ ├── login.html

│ └── dashboard.html

├── screenshots/

└── README.md

---

## Security Features

### Password Hashing

User passwords are never stored in plain text. Passwords are hashed using bcrypt before being saved to the database.

### SQL Injection Prevention

Parameterized SQL queries are used to prevent SQL injection attacks.

### Session Management

User sessions are securely managed using Flask session handling.

### Secure Authentication

Only users with valid credentials can access the protected dashboard.

---

## Workflow

1. User registers an account.
2. Password is hashed using bcrypt.
3. User information is stored in SQLite database.
4. User logs in using registered credentials.
5. Password hash is verified.
6. Session is created upon successful login.
7. User accesses dashboard.
8. User can securely logout.

---

## Screenshots

### Registration Page

(Add screenshot here)

### Login Page

(Add screenshot here)

### Dashboard

(Add screenshot here)

### Database Records

(Add screenshot showing hashed passwords)

---

## Sample Database Output

| ID | Username | Password Hash |
| -- | -------- | ------------- |
| 1  | lokesh   | $2b$12$...    |

Passwords are stored as bcrypt hashes instead of plain text.

---

## Future Enhancements

* Password Strength Validation
* Two-Factor Authentication (2FA)
* Password Reset Functionality
* Email Verification
* Account Lockout Mechanism
* Login Attempt Monitoring

---

## Conclusion

This Secure Login System demonstrates essential cybersecurity concepts such as authentication, password hashing, session management, and database security. The project provides a strong foundation for understanding secure web application development and user authentication mechanisms.
