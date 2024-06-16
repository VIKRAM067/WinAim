# Employee Management System (sql)

This repository contains the SQL schema and queries for a simple employee database.

## Tables

- `employees`
- `departments`
- `salaries`

## SQL Commands

### Create Tables

The SQL commands to create the tables are in `schema.sql`.

### Queries

The SQL queries are in `query_1.sql` , `query_2.sql` , `query_3.sql`.

1. Find all employees who have been hired in the last year.
2. Calculate the total salary expenditure for each department.
3. Find the top 5 highest-paid employees along with their department names.


# Inventory Management API

This project provides an API for managing inventory in warehouses. It allows warehouse managers to perform CRUD operations on products, suppliers, warehouses, and stock levels.

## Features

- **Products Management**: Create, read, update, and delete products.
- **Suppliers Management**: Create, read, update, and delete suppliers.
- **Warehouses Management**: Create, read, update, and delete warehouses.
- **Stock Levels Management**: Create, read, update, and delete stock levels.

  ## Endpoints

- **Products**:
`POST /products/`: Create a new product.
`GET /products/`: Get all products.
`GET /products/{product_id}`: Get a specific product by ID.
`PUT /products/{product_id}`: Update a product.
`DELETE /products/{product_id}`: Delete a product.

- **Suppliers**:
`POST /suppliers/`: Create a new supplier.
`GET /suppliers/`: Get all suppliers.
`GET /suppliers/{supplier_id}`: Get a specific supplier by ID.
`PUT /suppliers/{supplier_id}`: Update a supplier.
`DELETE /suppliers/{supplier_id}`: Delete a supplier.

- **Warehouses**:
`POST /warehouses/`: Create a new warehouse.
`GET /warehouses/`: Get all warehouses.
`GET /warehouses/{warehouse_id}`: Get a specific warehouse by ID.
`PUT /warehouses/{warehouse_id}`: Update a warehouse.
`DELETE /warehouses/{warehouse_id}`: Delete a warehouse.

- **Stock Levels**:
  `POST /stock-levels/`: Create a new stock level.
`GET /stock-levels/`: Get all stock levels.
`GET /stock-levels/{stock_level_id}`: Get a specific stock level by ID.
`PUT /stock-levels/{stock_level_id}`: Update a stock level.
`DELETE /stock-levels/{stock_level_id}`: Delete a stock level.

## Technologies Used

- **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.7+.
- **MySQL**: A widely used open-source relational database management system.


## Getting Started

### Prerequisites

- Python 3.7 or higher
- MySQL

### Installation and Running

1. Clone the repository:
2. Install dependencies:
`fastapi==0.70.0
uvicorn==0.15.0
python-dotenv==0.19.2
mysql-connector-python==8.0.28
`
3.Create a .env file in the root directory with the following configuration:
`MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=your_password
MYSQL_DATABASE=inventorymanagement
`
4.Run the application:
`uvicorn main:app --reload`





