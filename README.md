# Employee-Management-System
Description
This is command-line application from scratch to manage a company's employee database, using Node.js, Inquirer, and MySQL.This is a CLI app that allows a user to perform create, read, update, and delete (CRUD) functions on a SQL database representing the departments, roles and employees of a company. It is set up in a user friendly way, and requires no knowledge of SQL commands to operate.

Prerequisites
Git terminal
Node
MySQL and MySQL Workbench (or the terminal instead of MySQL Workbench)
Table of Contents
Installation
Usage
License
Contributing
Tests
Questions
Installation
The user should clone the repository from GitHub. This application requires Node.js, Inquirer, console.table and mysql2.Install all these packages by using npm install. To start application run npm start. To view database from MySQL run mysql -u root -p.

Usage
This application will allow users to view, add, and edit employees, roles, departments, and managers.

Constraints
To delete/update a department will also delete/update roles within the department

To delete a role will be rejected if any employee was given this role, and an error will be thrown; to update a role will also update every employee with the role

To delete a manager will set all report-tos manager to NULL, i.e. with no manager

