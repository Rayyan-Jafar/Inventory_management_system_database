# Inventory Management System

This project is a simple Inventory Management System built with a focus on database design and schema planning. It simulates how inventory data might be structured and managed in a small to medium-sized business environment.

The system uses an Excel-based database, making it accessible for beginners or those working without a full database engine. The project includes a well-defined schema and an ERD diagram to visualize the relationships between entities.

---

## Project Contents

- **Excel Database**  
  The core data for the inventory system is stored across multiple Excel sheets, each representing a table (e.g., Products, Suppliers, Orders).

- **Schema Description** (`schema(tables + keys).txt`)  
  This text file outlines the table structures, primary keys, and foreign key relationships. It helps explain how different parts of the system are connected.

- **Entity Relationship Diagram** (`ERD.png`)  
  A visual representation of the database design. This diagram shows the entities (tables), their attributes, and how they relate to each other.

---

## Tables and Relationships

Here is a brief overview of the main entities (tables):

- **Products**: Stores product details such as name, SKU, price, and quantity in stock  
- **Suppliers**: Contains supplier contact information  
- **Orders**: Represents customer orders, with dates and status  
- **OrderItems**: Links orders to products with quantity and pricing  
- **Categories**: Groups products into types or departments  

The full schema with keys is described in `schema(tables + keys).txt`.

---

## How to Use

1. Open the Excel file to view and interact with the database. Each sheet corresponds to a table in the system.

2. Review the schema file to understand the database structure:
