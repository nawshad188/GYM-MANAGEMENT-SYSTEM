# GYM-MANAGEMENT-SYSTEM
📌 Project Overview

The GYM Management System is a desktop-based application developed using C# Windows Forms and SQL Server (LocalDB) in Visual Studio 2019. The system is designed to manage daily gym operations such as member registration, login, package selection, payment processing, and member management with role-based access control. This project aims to reduce manual work, improve data accuracy, and provide an efficient way to manage gym members and activities.

✨ Features

🔐 Authentication & Authorization

Secure login system

Role-based access control

User roles:

a. Admin

b. Member


👤 Member Management

Register new members

Store personal information (Name, Email, Gender, Age)

Assign gym packages

View and manage member data

Secure login and logout


📦 Package Management

Assign packages during registration

Manage package information

Package-based access to gym services


💳 Payment Management

Payment option during registration

Payment verification process

Store payment records in database

Display payment confirmation


🧾 Admin Controls

View all registered members

Manage member information

Control system data

Access admin dashboard

Logout from system


👥 User Roles & Permissions

Admin: Full system access and member management

Member: Register, login, make payment, and access personal dashboard


🗃️ Database Structure

The project uses SQL Server LocalDB with the following main tables:

Admin

Members

Package

Payment

Relationships are implemented using primary keys and foreign keys to ensure data integrity and avoid data redundancy.


🛠️ Technologies Used

Programming Language: C#

Framework: .NET Framework (Windows Forms)

Database: SQL Server LocalDB

IDE: Visual Studio 2019


⚙️ Installation & Setup

Open the project in Visual Studio

Make sure SQL Server LocalDB is installed

Verify database connection string in the code

Data Source=(LocalDB)\MSSQLLocalDB;

AttachDbFilename=|DataDirectory|\dbGYM.mdf;

Build and run the project


▶️ How to Use

Launch the application

Register as a new member or login

Complete payment during registration

Access features based on user role

Admin can manage members from admin panel

Logout safely after use


📄 UML Diagrams Included

Use Case Diagram
Activity Diagram

ER Diagram

These diagrams explain system behavior, workflow, and database structure.


🎓 Purpose of the Project

This project was developed for academic purposes to demonstrate:
Windows Forms application development

SQL database integration

CRUD operations

Role-based access control

Real-world desktop application design


📌 Author

Md. Nawshad Hossain

GYM Management System


✅ License

This project is for educational use only.
