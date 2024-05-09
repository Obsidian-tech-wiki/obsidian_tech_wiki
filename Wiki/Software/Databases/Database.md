---
authors:
  - "0x4248"
tags:
  - Software
  - Databases
aliases:
  - database
  - Databases
  - databases
---
A **Database** is a organised collection of structured data. Databases are managed trough a database management system (DBMS). 
## Key concepts
A database have entities which are a category of an object. For example this can be name, age or username. Each entity in the database have attributes.

### Example table
| Name | Age | Username |
|------|-----|----------|
| John | 25  | john123  |
| Jane | 30  | jane321  |
| Jack | 22  | jack456  |
| Jill | 28  | jill789  |

In this table, the entities are Name, Age and Username. The attributes are the values in the table.

### Database ID's

Each row in a database table have a unique identifier called a primary key. This is used to identify the row in the table.

| ID | Name | Age | Username |
|----|------|-----|----------|
| 1  | John | 25  | john123  |
| 2  | Jane | 30  | jane321  |
| 3  | Jack | 22  | jack456  |
| 4  | Jill | 28  | jill789  |

The ID makes it easy to reference a row in the table and allow for easy update, delete and search operations.

## Flat file databases
**See main wiki page:** *[[Flat file database]]*
A flat file database is a database that stores data in a single file. This can be a simple and easy way to store data, but it can be hard to manage and scale when the data grows.

## Relational databases
**See main wiki page:** *[[Relational database]]*
A relational database is a database that stores data in tables and sometimes separate files. This is a more structured way to store data compared to flat file databases. Relational databases allow you to create relationships between tables and enforce constraints.

### Types of relationships
The most common types of relationships in a relational database are:
- One-to-One
- One-to-many
- Many-to-many

#### One to one
A one to one relationship is when one row in a table is related to one row in another table.

For example: Boss - Company. There is only one boss for each company.

#### One to many
A one to many relationship is when there is one row that is related to many rows in another table.

For example: Doctor - Patient. A dentist will be related to several patients.

#### Many to many
A many to many relationship is when there are many rows linked to many other rows in a other table.

For example: Costumer account - Product. A single account can order many products on to their account.

### Entity relationship modelling
Relationships in a database can be modelled to show the relationship between the entities.
![[Entity relationship modelling]]

