
# EHR_DatabaseProject

This project demonstrates how to manage healthcare-related data (Electronic Health Records) using both **structured** (MySQL) and **non-structured** (MongoDB) databases. It includes various SQL queries, stored procedures, and MongoDB operations to illustrate real-world scenarios such as CRUD operations, handling transactions, working with joins, and more.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Folder Structure](#folder-structure)
3. [MySQL Queries](#mysql-queries)
4. [MongoDB Queries](#mongodb-queries)
5. [How to Use](#how-to-use)
6. [License](#license)

---

## Project Overview
- **Objective**: Provide a sample Electronic Health Record (EHR) database setup with operations in both MySQL and MongoDB.
- **Scope**: Showcases fundamental and advanced database features:
  - **MySQL**: CRUD operations, stored procedures, joins, transactions, and various insert queries.
  - **MongoDB**: Sample queries for handling non-structured healthcare data.

The primary goal is to give an example of how healthcare systems can store and manage patient data, prescriptions, vitals, and other related information using both relational and NoSQL approaches.

---

## Folder Structure





























Inside **MySQL Queries.zip**, you will find:
1. **1. SQL Queries CRUD Operations (Adv.Database).sql**  
2. **2. Stored procedure_Self Vitals record data table.sql**  
3. **3. Stored procedure_prescription_data table.sql**  
4. **4. Other Combinations of Insert SQL Queries.sql**  
5. **5. JOIN SQL Query.sql**  
6. **6. Transaction Operation SQL Queries.sql**  

Inside **Mongodb_project.zip**, you will find:
- MongoDB scripts (CRUD operations, indexing, aggregation, etc.) related to the same EHR context.

---

## MySQL Queries

1. **CRUD Operations**  
   - Basic Create, Read, Update, and Delete statements for core tables such as patients, prescriptions, vitals, etc.

2. **Stored Procedures**  
   - **Vitals Procedure**: Demonstrates how to store and retrieve patient vitals data.
   - **Prescription Procedure**: Shows how to handle prescription-related data (medications, dosages, etc.).

3. **Insert Combinations**  
   - Various SQL INSERT queries that populate multiple tables with sample data, ensuring referential integrity.

4. **JOIN Queries**  
   - Examples of different JOIN types (INNER, LEFT, RIGHT) to retrieve combined data from multiple tables.

5. **Transaction Queries**  
   - Illustrates how to manage atomic operations using `START TRANSACTION`, `COMMIT`, and `ROLLBACK` to ensure data consistency.

---

## MongoDB Queries

The MongoDB queries cover:
- **CRUD Operations**: Insert, find, update, and delete documents in collections such as `patients`, `prescriptions`, and `vitals`.
- **Aggregation Pipelines**: Demonstrates how to perform more complex data processing directly in MongoDB.
- **Indexing**: Shows how to create indexes for faster queries on large datasets.
- **Schema Design Examples**: Illustrates storing nested documents and references that might mirror EHR data structures.

---

## How to Use

### MySQL
1. **Setup a Database**: Create a new MySQL database (e.g., `ehr_db`).
2. **Run the Scripts**:  
   - Open each `.sql` file in MySQL Workbench (or any SQL client).  
   - Execute them in the logical order (e.g., create tables first, then run insert queries, then stored procedures).
3. **Verify**: Check that all tables, data, and stored procedures are created successfully.

### MongoDB
1. **Start MongoDB**: Ensure your MongoDB server is running locally or remotely.
2. **Import or Run Scripts**:  
   - Use the Mongo Shell or MongoDB Compass to execute the queries from the `Mongodb_project.zip`.
   - Adjust any database or collection names if needed.
3. **Test**: Verify that the collections are created and the sample data is inserted correctly.

---

## License

This project is licensed under the MIT License. (Include or reference the actual LICENSE file in my repository.)

---

**Thank you for exploring the EHR_DatabaseProject!**  
If you have any questions or suggestions, feel free to open an issue or reach out.



