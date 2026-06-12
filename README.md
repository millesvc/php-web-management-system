# PHP Web Management System

A web management system built with PHP and MySQL, designed to demonstrate authentication workflows, database integration, session management and modular backend development.

## Overview

This project implements a structured web application that allows users to authenticate, manage information and interact with a database through a secure and organized architecture.

The application follows a modular design approach, separating responsibilities across different components to improve maintainability, scalability and code readability.

## Features

* User authentication
* Login and registration system
* Session management
* Database integration with MySQL
* Input validation
* Modular architecture
* Structured backend organization
* Secure data handling

## Technologies

* PHP 7.3+
* MySQL
* HTML5
* CSS3
* SQL

## Project Structure

```text
project/
│
├── config/
│   └── database.php
│
├── public/
│   └── index.php
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── services/
│   └── validators/
│
├── schema.sql
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/millesvc/php-web-management-system.git
cd php-web-management-system
```

### Create the database

Create a MySQL database:

```sql
CREATE DATABASE auth_system;
```

### Import the schema

Import the provided `schema.sql` file into the database.

### Configure database credentials

Edit the file:

```text
config/database.php
```

and update the connection settings according to your local environment.

### Start the development server

```bash
php -S localhost:8000 -t public
```

### Access the application

```text
http://localhost:8000
```

## Learning Outcomes

This project was developed to strengthen practical knowledge in:

* Backend development with PHP
* Database management
* Authentication systems
* Session handling
* Software architecture
* Modular programming
* Input validation and security practices

## Future Enhancements

* Password recovery functionality
* Role-based access control
* REST API integration
* Activity logging
* User profile management
* Administrative dashboard

## Author

MillesVC

Civil Informatics Engineering Student
Software Development • Data Analysis • Web Technologies
