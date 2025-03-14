
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

```text
EHR_DatabaseProject/
├── LICENSE
├── MySQL Queries.zip
│   ├── 1. SQL Queries CRUD Operations (Adv.Database).sql
│   ├── 2. Stored procedure_Self Vitals record data table.sql
│   ├── 3. Stored procedure_prescription_data table.sql
│   ├── 4. Other Combinations of Insert SQL Queries.sql
│   ├── 5. JOIN SQL Query.sql
│   └── 6. Transaction Operation SQL Queries.sql
├── Mongodb_project.zip
│   ├── download_from_mongofiles/
│   ├── upload_to_mongofiles/
│   └── MongoDB_Database_Query.mongodb
└── README.md
```



Inside **MySQL Queries.zip**, you will find:
- SQL Queries CRUD Operations (Adv.Database).sql
- Stored procedure_Self Vitals record data table.sql
- Stored procedure_prescription_data table.sql 
- Other Combinations of Insert SQL Queries.sql  
- JOIN SQL Query.sql
- Transaction Operation SQL Queries.sql

   
Inside **Mongodb_project.zip**, you will find:
- MongoDB scripts (CRUD operations, and aggregation) related to the same EHR context.

---

## MySQL Queries

1. **CRUD Operations**  
   - Basic Create, Read, Update, and Delete statements for core tables such as doctor, patients, prescriptions, vitals, and appoinments.

2. **Stored Procedures**  
   - **Vitals Procedure**: Demonstrates how to store and retrieve patient vitals data.
   - **Prescription Procedure**: Shows how to handle prescription-related data (medications). 

3. **Insert Combinations**  
   - Various SQL INSERT queries that insert values in these tables with sample data, ensuring referential integrity.

4. **JOIN Queries**  
   - Examples of different JOIN types (INNER, LEFT) to retrieve combined data from multiple tables.

5. **Transaction Queries**  
   - Illustrates how to manage atomic operations using `START TRANSACTION`, `COMMIT`, and `ROLLBACK` to ensure data consistency.

---

## MongoDB Queries

The MongoDB queries cover:
- **CRUD Operations**: Insert, find, update, and delete documents in collections such as `patient_data_table`, and `doctor_data_table`.
- **Aggregation Pipelines**: Demonstrates how to perform lookup/aggregation operation between this two collections/tables.
- **Schema Design Examples**: Illustrates storing nested documents and references that might mirror EHR data structures.

---

## How to Use

### MySQL
1. **Setup a Database**: Create a new MySQL database (e.g., `ehr_portal`).
2. **Run the Scripts**:  
   - Open each `.sql` file in MySQL Workbench (or any SQL client).  
   - Execute them in the logical order (e.g., create/use the database, create tables first, then run insert queries, then stored procedures, then run select/update/delete queries).
3. **Verify**: Check that all tables, data, and stored procedures are created successfully.

### MongoDB
1. **Start MongoDB**: Ensure your MongoDB server is running locally or remotely.
2. **Import or Run Scripts**:  
   - Use the Mongo Shell or MongoDB Compass to execute the queries from the `Mongodb_project.zip`. The queries consist of the following:
     - Create a MongoDB database named `ehr_portal_mongo`.
     - Create collections/tables named `patient_data_table` and `doctor_data_table`.
     - Insert the corresponding values from the SQL database for patients and doctors.
     - Upload the associated medical report file and link it to the data.
     - Connect the patient and doctor collections/tables by `date_of_visit` and `time_of_visit` using lookup and aggregation functions.
3. **Test**: Verify that the collections are created and the sample data is inserted correctly.

---

## License

This project is licensed under the MIT License. (Include or reference the actual LICENSE file in my repository.)

---

**Thank you for exploring the EHR_DatabaseProject!**  
If you have any questions or suggestions, feel free to open an issue or reach out.



