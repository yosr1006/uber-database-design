# uber-database-design
PostgreSQL schema and full database dump for an Uber project, ready to run and test.
# Uber Database Design (PostgreSQL)

This repository contains the database design and implementation of an Uber-like system using **PostgreSQL**.

## 📂 Files
- **uber_schema.txt** → Contains only the database schema (tables and constraints) with comments for clarity.  
- **uber_full_database.sql** → Full PostgreSQL dump including both the schema and all data inserts.  
   👉 This file can be directly imported into PostgreSQL to recreate the database with sample data ready for testing and queries.

## 🛠️ Technologies
- PostgreSQL (psql)

## 🚀 How to Use
1. To view only the database design, run:
   ```bash
   \i uber_schema.sql 
2. To import the full database with data, run:
  ```bash
  \i uber_full_database.sql
```
## 👩‍💻Notes
The schema file highlights my database design (tables, keys, and relationships).
The dump file provides a complete working example with sample data for experimentation.
