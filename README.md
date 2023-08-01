# SQL-DataBase-Fundamentals
This Repo Contains fundamental knowledge of RDBMS You Need to Know
# DataBase
It is a structured collection of data that is organized and stored in a way that allows for efficient 
retrieval, manipulation, and management of information.
## Why to use DB over normal files?
 ### a) Data Integrity and Consistency
Databases provide mechanisms for defining constraints and rules that ensure data integrity and consistency. Constraints like primary keys, foreign keys, and unique constraints prevent the insertion of duplicate or inconsistent data.
 ### b) Indexing 
Databases utilize indexes to speed up data retrieval operations, making queries more efficient, even with large datasets.
 ### c) Data Relationships and Joins 
Databases support the establishment of relationships between tables through foreign keys.
 ### d) Data Backup and Recovery
Databases often offer built-in backup and recovery features, ensuring that critical data is protected from loss due to hardware failures, accidental deletions, or disasters.
 ### e) Data Security
Databases offer built-in security features that allow administrators to control access to the data at different levels.
# Database componenets
## 1- Schema
The database schema defines the structure of the database, including the tables, their columns, Views and Procedures, It acts as a blueprint for organizing the data.
## 2- Tables
Data in a database is organized into tables, which are composed of rows and columns. Each row represents a single record or data entry, and each column represents a specific attribute or field of the data.
Primary Key: One or more columns in a table can be designated as the primary key. The primary key uniquely identifies each row in the table, ensuring that no two rows have the same identifier.
## 3- Indexing 
Databases often automatically create indexes for certain columns in a table. Indexes enhance the performance of data retrieval operations ex: primary key and foreign key.
The most common type of index is the "B-tree" (Balanced Tree) index, which is used for typical indexing needs. There are also other specialized index types like bitmap indexes, hash indexes, and full-text indexes, each suited for specific use cases.
### Indexing Trade-offs
it requires additional disk space and resources. Also, when data is inserted, updated, or deleted in the table, the corresponding changes must be applied to the index which make write operations more slower.
## 4- Relationships
Relationships define how different tables in the database are related to each other. These relationships are established through foreign keys.
foreign key is a column or a set of columns in a table that establishes a relationship with the primary key of another table.
### Types of Relations
One-to-One Relationship: each record in one table is related to at most one record in another table, it's used to split a table with many columns into two separate tables ex: Employee and EmployeeProfile.
![image](https://github.com/elsayedzahran/SQL-DataBase-Fundamentals/assets/68614758/142f12fb-88e0-4d47-8db0-b67672f0a3ea)
One-to-Many Relationship: each record in one table can be related to one or more records in another table. This is the most common type of relationship in relational databases ex: Employee and Department.
![image](https://github.com/elsayedzahran/SQL-DataBase-Fundamentals/assets/68614758/1847f036-ff09-470d-9f95-439dd5e3f954)

Many-to-Many Relationship: each record in one table can be related to multiple records in another table, and vice versa. To represent a many-to-many relationship in a relational database, a junction table (also called a linking or associative table) is used ex: Student and Course.



