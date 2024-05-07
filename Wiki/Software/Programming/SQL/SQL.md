---
authors:
  - "0x4248"
tags:
  - Software
  - Programming
  - SQL
aliases:
  - sql
  - Structured query language
  - structured query language
---
**SQL** or **Structured query language** is a language that is used to query and update tables in relational databases. It can also be used to create tables.

## Basics
SQL is a declarative language, meaning that you specify what you want to do, not how you want to do it. SQL is not case-sensitive, but it is common practice to write SQL keywords in uppercase.

### SELECT
The `SELECT` statement is used to query data from a table. The basic syntax is:
```sql
SELECT column1, column2, ...
FROM table_name;
```
You can also use the `*` wildcard to select all columns:
```sql
SELECT *
FROM table_name;
```

### WHERE
The `WHERE` clause is used to filter records. The basic syntax is:
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```

### INSERT
The `INSERT INTO` statement is used to insert new records into a table. The basic syntax is:
```sql
INSERT INTO table_name (column1, column2, ...)
VALUES (value1, value2, ...);
```

### UPDATE
The `UPDATE` statement is used to update existing records in a table. The basic syntax is:
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

### DELETE
The `DELETE` statement is used to delete records from a table. The basic syntax is:
```sql
DELETE FROM table_name
WHERE condition;
```

### CREATE TABLE
The `CREATE TABLE` statement is used to create a new table. The basic syntax is:
```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    ...
);
```