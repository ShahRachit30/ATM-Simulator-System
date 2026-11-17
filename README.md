# ATM Bank Management System

A Java-based ATM and Bank Management System developed using Java Swing and MySQL. The application provides a graphical interface for performing basic banking operations, managing customer accounts, and viewing transaction information.

## Features

- User Login
- New Account Registration
- Customer Information Management
- Balance Enquiry
- Cash Deposit
- Cash Withdrawal
- Fast Cash
- PIN Change
- Mini Statement
- Transaction Management

## Technologies Used

- **Programming Language:** Java
- **GUI:** Java Swing
- **Database:** MySQL
- **Database Connectivity:** JDBC
- **IDE:** NetBeans
- **External Library:** JCalendar

## Project Structure

```text
ATM-Bank-Management-System/
│
├── database/
│   └── mysql.sql
│
├── src/
│   ├── ASimulatorSystem/
│   │   ├── BalanceEnquiry.java
│   │   ├── Conn.java
│   │   ├── Deposit.java
│   │   ├── FastCash.java
│   │   ├── Login.java
│   │   ├── MiniStatement.java
│   │   ├── Pin.java
│   │   ├── Signup.java
│   │   ├── Signup2.java
│   │   ├── Signup3.java
│   │   ├── Transactions.java
│   │   └── Withdrawl.java
│   │
│   ├── icons/
│   └── lib/
│
├── .gitignore
├── LICENSE
└── README.md
```

## Prerequisites

Before running the application, install:

1. Java Development Kit (JDK).
2. MySQL Server.
3. MySQL Connector/J.
4. JCalendar library (jcalendar-1.4.jar).

## Database Setup

1. Start your MySQL server.
2. Open MySQL Workbench or another MySQL client.
3. Open the SQL file located in `database/mysql.sql`.
4. Execute the SQL statements to create the database and required tables.

The application uses a database named:

`bankmanagementsystem`

## Configuration

Update the database connection settings in `Conn.java` according to your MySQL configuration.

Make sure the MySQL Connector/J driver is added to the project classpath.

Also, add the JCalendar library to the project classpath.

Do not commit personal database credentials to the repository.

## Running the Application

1. Clone this repository.
2. Open the project in your preferred Java IDE.
3. Configure the required external libraries.
4. Set up the MySQL database.
5. Configure the database connection.
6. Run `Login.java` to start the application.

## Future Improvements

- Improved database security.
- Better input validation.
- Enhanced user interface.
- Improved transaction management.
- Secure password and PIN handling.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.