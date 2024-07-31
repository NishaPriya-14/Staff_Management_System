# Staff_Management_System

## Overview
The Staff Management System is a Java-based application developed using NetBeans. It allows users to add staff, remove staff, view staff details, and rate staff. The application uses a SQL database for storing and managing staff information.

## Features
- **Add Staff:** Add new staff members to the database.
- **Remove Staff:** Remove existing staff members from the database.
- **Staff Details:** View detailed information about staff members.
- **Ratings:** Rate staff members based on their performance.

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- NetBeans IDE
- MySQL Database (or any SQL database)
- JDBC Driver for the SQL database

### Database Setup
1. Create a database named `staff_management`.
2. Run the SQL scripts located in the `sql/` directory to create the necessary tables and populate initial data.
   ```sh
   mysql -u root -p staff_management < sql/schema.sql
   mysql -u root -p staff_management < sql/data.sql


### Clone the Repository
```sh
git clone https://github.com/NishaPriya-14/staff-management-system.git
cd staff-management-system
