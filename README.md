# Workshop1---IRIS-ONE-CARE-SYSTEM---CPP
My first project at UTeM. I built a contact lens management system using C++ and MySQL that handles everything from user logins to inventory and generating sales reports. Learnt how to draw flow charts, Entity-Relationship Diagrams and implement it into system by connecting the codings with MySQL database.

**Overview**
Iris One Care is a terminal-based online shopping management system developed to assist store managers and customers in buying contact lens. The system handles everything from user and staff registration to generating sales report.  

**Core Functionalities**
- Authentication: Multi-level login for Admins, Staff, and Customers.  
- Inventory Management: Full CRUD (Create, Read, Update, Delete) capabilities for product stock.  
- Sales Analysis: Automated generation of monthly total sales reports.  
- Database Integration: Real-time data persistence using MySQL.  
- Technical StackLanguage: C++   
- Database Used: MySQL   
- IDE: Microsoft Visual Studio   

System Architecture
The project is built on a structured modular design:

Customer Module: Create orders, view order history, and process payments.  
Staff Module: Manage customer profiles and view order logs.  
Admin Module: Advanced inventory control and financial reporting.  

As a Cybersecurity student, I've identified the following areas that requires future hardening for this small project I created during Workshop 1:

Credential Security: Currently, passwords are stored in plain text. Future versions will implement SHA-256 hashing.  
Input Validation: Added error handling to prevent invalid authorization codes during staff registration.
Data Integrity: Identified a logic constraint where stock does not auto-update on canceled payments.  
