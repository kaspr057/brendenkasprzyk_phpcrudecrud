# PHP Crude CRUD Application

This repository contains the source code for **PHP Crude CRUD**, a simple three-tier, data-driven web application. The project demonstrates the core concepts of web application development, deployment, and management in a Linux-based environment, following a full-stack approach. 

The application connects to a MySQL database to perform basic CRUD (Create, Read, Update, Delete) operations, showcasing how PHP can interact with a database layer in a structured, scalable manner.

---

## Project Overview

This project was designed to simulate real-world development and deployment workflows, including virtual machine setup, server configuration, and application deployment. 

### Key Features:
- **Three-tier Architecture:** Separation of presentation, application logic, and data layers.
- **CRUD Functionality:** Users can perform basic Create, Read, Update, and Delete operations on the database records.
- **Database Integration:** Preloaded with a sample schema containing **300,000 records** for testing performance and scalability.

---

## Development and Deployment Process

This project involved the following steps:

1. **Virtual Machine Setup**
   - Created a virtual machine to host the application.
   - Installed and configured **Ubuntu** as the operating system.

2. **System Configuration**
   - Updated and upgraded the system packages.
   - Configured the machine for **dual network connections** (NAT and bridged).

3. **LAMP Stack Installation**
   - Installed and configured the components of a LAMP stack:
     - **Linux** (Ubuntu)
     - **Apache** web server
     - **MySQL** database
     - **PHP** for server-side scripting.

4. **MySQL Configuration**
   - Configured MySQL with secure user accounts and appropriate permissions.
   - Loaded a sample schema containing 300,000 records for testing.

5. **PHP Application Development**
   - Developed PHP scripts to handle CRUD operations using database connectors.
   - Configured database credentials securely within the application.

6. **Version Control**
   - Used **GitHub** for source code management and collaboration.

7. **Deployment**
   - Packaged the application into a `tar.gz` file for distribution.
   - Deployed and tested the application in additional VM environments to verify compatibility.

---
