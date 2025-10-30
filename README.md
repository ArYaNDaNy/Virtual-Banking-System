<div align="center">

  <h1>Virtual-Banking-System</h1>
  <p><em>A Java Swing & MySQL application for secure and efficient banking operations.</em></p>
  
  <p>
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/ArYaNDaNy/Virtual-Banking-System?style=flat&logo=git&logoColor=white&color=0080ff">
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/ArYaNDaNy/Virtual-Banking-System?style=flat&color=0080ff">
    <img alt="Repo size" src="https://img.shields.io/github/repo-size/ArYaNDaNy/Virtual-Banking-System?style=flat&color=0080ff">
  </p>
  
  <p>
    <em>Built with:</em><br>
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00.svg?style=flat&logo=openjdk&logoColor=white">
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1.svg?style=flat&logo=mysql&logoColor=white">
  </p>

</div>

<hr>

## 📋 Table of Contents

* [Overview](#overview)
* [Key Features](#key-features)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Database Setup](#database-setup)
  * [Installation & Usage](#installation-usage)  * [License](#license)

<hr>

## Overview

This project is a banking management application built with **Java Swing** for the user interface and **MySQL** for secure data storage. It supports core banking features such as account creation, deposits, withdrawals, balance checks, and transaction history tracking.

The system provides a clean and interactive UI, role-based access (admin/customer), and real-time database connectivity to ensure accurate and efficient banking operations.

## Key Features

* **🔒 Secure User Accounts:** Full account creation and management.
* **💸 Core Banking Operations:** Deposit, withdraw, and check balance.
* **🧾 Transaction History:** View a complete history of all transactions.
* **🧑‍💼 Role-Based Access:** Separate functionalities for customers and administrators.
* **🖥️ Clean UI:** A user-friendly and interactive interface built with Java Swing.
* **⚡ Real-Time Data:** Direct connectivity to a MySQL database for live, accurate data.

<hr>

## Getting Started

Follow these instructions to get a local copy of the project up and running.

### Prerequisites

You must have the following software installed on your machine:

* [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (e.g., JDK 11 or higher)
* [MySQL Server](https://dev.mysql.com/downloads/mysql/)
* [Git](https://git-scm.com/)

### Database Setup

Before running the application, you must set up the database.

1.  Open your MySQL command-line client or a GUI tool (like MySQL Workbench).
2.  Create a new database for the project.
    ```sql
    CREATE DATABASE bank_database; 
    ```
    *(**Note:** If your database name is different, please update it in the `Conn.java` or database connection file.)*

3.  Select the database:
    ```sql
    USE bank_database;
    ```
4.  Run the SQL script included in the repository to create the required tables.
    *(**User Task:** Please add the command to run your `.sql` file here, for example:)*
    ```sql
    SOURCE /path/to/your/schema.sql;
    ```


### Installation & Usage

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/ArYaNDaNy/Virtual-Banking-System.git](https://github.com/ArYaNDaNy/Virtual-Banking-System.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Virtual-Banking-System
    ```
3.  **Compile the Java files:**
    *(**Note:** This command may need to be adjusted based on your project structure and if you are using a build tool like Maven or Gradle.)*
    ```sh
    javac *.java 
    ```
4.  **Run the application:**
    *(**Note:** Please replace `Login` with the name of your main Java file that contains the `main` method.)*
    ```sh
    java Login
    ```

<hr>

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

<hr>
<div align="left">
  <a href="#top">⬆ Return to Top</a>
</div>
