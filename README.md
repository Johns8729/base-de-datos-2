# RiwiSupply Database Project

## Project Description

This project was developed as part of the Relational Databases module.

The objective is to analyze an Excel dataset containing redundant and inconsistent information, normalize the data up to Third Normal Form (3NF), design an Entity-Relationship Model (ERM), implement the database in PostgreSQL, and create SQL scripts for data manipulation and reporting.

---

## Technologies Used

- PostgreSQL
- pgAdmin 4
- SQL
- dbdiagram.io

---

## Database Engine

- PostgreSQL

---

## Normalization Process

The original dataset contained redundant information about suppliers, cities, warehouses, products, and categories.

The normalization process included:

- First Normal Form (1NF): Removed repeating groups and ensured atomic values.
- Second Normal Form (2NF): Separated data into independent tables to eliminate partial dependencies.
- Third Normal Form (3NF): Removed transitive dependencies by creating relationships between entities.

---

## Database Structure

The database contains the following tables:

- City
- Supplier
- Warehouse
- Category
- Product
- Purchase_Order
- Inventory_Movement

These tables are connected using primary keys and foreign keys to ensure data integrity.

---

## Entity Relationship Model

The Entity Relationship Model (ERM) represents:

- Suppliers
- Cities
- Warehouses
- Categories
- Products
- Purchase Orders
- Inventory Movements

All relationships follow Third Normal Form (3NF).

---

## Instructions to Create the Database

1. Open pgAdmin.
2. Create a new PostgreSQL database.
3. Execute the DDL script.
4. Verify that all tables were created successfully.

---

## Instructions to Load Data

1. Open each table.
2. Import the CSV files or execute the INSERT scripts.
3. Verify the imported data.

---

## SQL Queries

The project includes SQL scripts for:

- Registering a new supplier and product.
- Updating supplier information.
- Deleting products without inventory movements.
- Stock available by product.
- Inventory movements by warehouse.
- Total purchases by supplier.
- Number of movements by warehouse.
- Product with the highest purchase volume.
- Total inventory value by warehouse.

---

## Developer Information

**Name:** John sebastian 

**Clan:** Clan 1 magdalena 
respository: https://github.com/Johns8729/base-de-datos-2
