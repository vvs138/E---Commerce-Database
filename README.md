# E-Commerce Database Project

## Overview
This project is a simple SQL-based database structure designed for an e-commerce application. It provides a relational model to store information about users, products, orders, and order items. With this project, you can showcase your foundational SQL skills, demonstrating your understanding of database creation, manipulation, and querying.

## Project Structure
The E-Commerce Database contains four main tables:

- **Users**: Stores user account information such as usernames, passwords, and emails.
- **Products**: Stores product details, including product name, price, stock quantity, and descriptions.
- **Orders**: Stores order details like user ID, order date, and total amount.
- **Order_Items**: Stores individual items within each order, specifying the product, quantity, and associated order ID.

## Features
- **User Management**: Add, retrieve, and manage user data.
- **Product Management**: Add, retrieve, and manage products with pricing and stock information.
- **Order Processing**: Track user orders and associated items.
- **Advanced Queries**: Includes a variety of queries, from basic CRUD operations to complex joins, aggregations, and reporting.

## Requirements
- SQL-compatible database management system (e.g., MySQL, PostgreSQL)
- Basic SQL knowledge for interacting with the database.

## Database Schema
Here's a brief look at the database schema:

- **Users**: 
  - `UserID` (PK)
  - `Username`
  - `Password`
  - `Email`
  - `CreatedAt`
  
- **Products**:
  - `ProductID` (PK)
  - `ProductName`
  - `Price`
  - `Stock`
  - `Description`
  - `CreatedAt`

- **Orders**:
  - `OrderID` (PK)
  - `UserID` (FK)
  - `OrderDate`
  - `TotalAmount`

- **Order_Items**:
  - `OrderItemID` (PK)
  - `OrderID` (FK)
  - `ProductID` (FK)
  - `Quantity`

