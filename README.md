# SQL Assignment Week 1


## *What You'll Need*
- A computer with internet access.
- A code editor (e.g., Visual Studio Code).
- MySQL Workbench or another SQL database environment.

---



## *Submission Instructions*
1. Answer every question below and put your responses in a file named `answers.md`
2. Push your completed `answers.md` file to your GitHub repository.
3. Submit the GitHub link for review.

---

## **Assignment Questions**

1. State and Explain the components of a DBMS(Database Management System)

Database Engine: The core service that processes and retrieves data from the database. It handles CRUD (Create, Read, Update, Delete) operations.
Data Definition Language (DDL): Manages the schema or structure of the database (e.g., creating tables, altering schema).
Data Manipulation Language (DML): Handles the manipulation of data within the database (e.g., querying, inserting, updating).
Database Manager: Ensures data integrity and security, managing access to the database.
Query Processor: Parses and executes queries, optimizing performance.
Transaction Manager: Manages transaction execution to maintain ACID properties (Atomicity, Consistency, Isolation, Durability).
Storage Manager: Handles the storage, retrieval, and updating of data on disk.
User Interface: Allows interaction between the user and the database, often through GUIs or command-line tools.

2. What is a relational database? Give 4 examples.

A relational database organizes data into tables (relations) where rows represent records and columns represent attributes. It uses a structured query language (SQL) for managing data. Relationships between tables are defined by primary and foreign keys.

Examples of Relational Databases:
MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database

3. State and Explain three classifications of SQL?
Data Definition Language (DDL):

Used to define and modify the structure of the database.
Commands: CREATE, ALTER, DROP, TRUNCATE.
Example: CREATE TABLE students (id INT, name VARCHAR(50));
Data Manipulation Language (DML):

Focuses on data retrieval and manipulation within the tables.
Commands: SELECT, INSERT, UPDATE, DELETE.
Example: INSERT INTO students (id, name) VALUES (1, 'John Doe');
Data Control Language (DCL):

Manages access control and permissions.
Commands: GRANT, REVOKE.
Example: GRANT SELECT ON students TO user1;

4. What is the difference between a Primary Key and a Foreign Key?
Primary Key	
A unique identifier for a record in a table.
Cannot contain NULL values.
Must be unique across the table.
Example: id in a students table.

Foreign Key
Establishes a relationship between two tables.
Can contain NULL values if not mandatory.
Refers to the primary key of another table.
Example: student_id in grades table referencing id in students.

6. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) visually represents the relationships between entities in a database. Entities represent tables, attributes represent columns, and relationships show how tables interact.

Components:
Entities: Represent objects (e.g., Student, Course).
Attributes: Properties of entities (e.g., Name, Age).
Relationships: Associations between entities (e.g., "enrolled in").
Cardinality: Defines the number of relationships (e.g., one-to-many).

7. What are the advantages of relational databases?
Data Integrity: Ensures data accuracy and consistency.
Flexibility: Allows complex queries with SQL.
Normalization: Reduces redundancy and improves efficiency.
Data Security: Offers robust access control mechanisms.
Scalability: Easily scales for growing datasets.

8. State four types of data type used to store data in tables?
Integer (INT): Stores whole numbers.
Character (CHAR/VARCHAR): Stores text strings.
Date and Time (DATE, DATETIME): Stores date and time values.
Floating-Point (FLOAT, DECIMAL): Stores decimal numbers for precision.

10. What is the purpose of a database management system (DBMS)?  
Efficiently Store and Retrieve Data: Facilitates quick access to large datasets.
Ensure Data Integrity: Maintains data accuracy and consistency.
Support Data Security: Controls user access and protects data.
Simplify Data Management: Provides tools for backup, recovery, and updates.
Facilitate Data Sharing: Enables multiple users or applications to access data concurrently.






*How to edit a [markdownfile](https://www.markdownguide.org/basic-syntax/#headings)*

###  NOTE: You should not fork the repository
