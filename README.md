🛒 E-commerce Database Management System
📌 Project Overview

This project implements a relational database system for an E-commerce Store using MySQL.
It provides a structured way to manage customers, products, categories, orders, payments, reviews, and addresses while ensuring data integrity, normalization, and relationships between entities.

The database schema is designed with:

✅ 1NF, 2NF, and 3NF compliance

✅ Proper Primary Keys, Foreign Keys, Unique, and Not Null constraints

✅ One-to-One, One-to-Many, and Many-to-Many relationships

✅ Support for views to simplify reporting

📂 Database Schema
Key Entities and Relationships:

Customers → Manage customer details

Customer Profiles → One-to-One relationship with customers

Addresses → Customers can have multiple addresses (One-to-Many)

Products & Categories → Many-to-Many via product_categories

Orders & Order Items → Many-to-Many between customers and products

Payments → Linked to orders

Reviews → Customers can leave reviews for products
