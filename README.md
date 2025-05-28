# 🛍️ Multi-Branch Boutique Database Management System

**Course:** CS2071 - Databases  
**Tools Used:** SQL & Visual Basic  
**Team Members:** Araa, Ehdaa, Marh, Wala  

## Project Overview

This project is a **Database Management System (DBMS)** for a growing boutique chain that sells a variety of dresses across multiple branches. The system is designed to manage all core entities involved in the business, including branches, staff, customers, products, and orders. It supports both in-store and online purchases, ensuring smooth data handling and consistency.

## Repository Structure

```bash
repository/
├── Boutique SQL.txt       # SQL scripts: schema creation and sample queries
├── Final_Report.pdf       # Full documentation: ER Diagram, Schema Design, Visual Basic UI

```

## System Description
### 1. Branch Management
- Each branch has a unique branch number, address (city, state, street, zip), and up to 3 phone numbers.
- Tracks data for multiple branches across regions.

### 2. Staff Management
- Each staff member has: ID, name, position (manager/employee), sex, age, phone, address, salary, and associated branch.
- Each branch has one manager and multiple employees.

### 3. Customer Information
- Each customer has a unique customer ID, full name, phone number, email, and credit limit.
- Customers may purchase directly from a branch or order via the Boutique mobile app.

### 4. Product Catalog
- Each product includes: product number, collection name (e.g., Spring 2022), size, color, available quantity, and price.
- Products are branch-specific for quantity tracking.

### 5. Orders
- Each order includes: order number, order date, product number, quantity, total amount, and shipping address (city, state, street, zip) with phone details.
- Orders are prepared and shipped by the assigned staff.

## Features
- SQL-based **database schema design**
- Full **Entity-Relationship (ER) diagram** and normalized schema
- **Visual Basic user interface** for managing and querying the system
- Supports operations like:
  - Adding and updating customer/staff/product records
  - Placing and managing orders
  - Branch-level data access and reporting

## Learning Outcomes
- Mastery of SQL for data modeling and complex queries
- Practical use of ER diagrams for real-world business systems
- Integration of databases with front-end applications using Visual Basic
- Collaborative software development experience

## Contributors
1. Araa AlMarhabi
2. Ehdaa AlMarhabi
3. Marh AlMutairi
4. Wala Oudah

