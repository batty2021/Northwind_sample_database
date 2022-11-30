# Northwind_sample_database
using SQL to retrieve, manipulate, update, delete, and perform complex operations like joins on the data present in the Northwind Sample database.


# Some of The Most Important SQL Commands
SELECT - extracts data from a database

UPDATE - updates data in a database

DELETE - deletes data from a database

INSERT INTO - inserts new data into a database

CREATE DATABASE - creates a new database

ALTER DATABASE - modifies a database

CREATE TABLE - creates a new table

ALTER TABLE - modifies a table

DROP TABLE - deletes a table

CREATE INDEX - creates an index (search key)

DROP INDEX - deletes an index


- The SELECT DISTINCT statement is used to return only distinct (different) values.
# SELECT DISTINCT Syntax
         SELECT DISTINCT column1, column2, ...
               FROM table_name;
- The WHERE clouse is used to filter records that fulfill a specified conditio
   # WHERE syntax  
       SELECT column1, column2, ...
         FROM table_name
           WHERE condition;
  # Text Fields vs. Numeric Fields
SQL requires single quotes around text values (most database systems will also allow double quotes).
However, numeric fields should not be enclosed in quotes:

# Operators in The WHERE Clause
 -  = , > , < ,>= , <= ,<>	Not equal. Note: In some versions of SQL this operator may be written as != , BETWEEN
 LIKE,IN

# The SQL AND, OR and NOT Operators
The WHERE clause can be combined with AND, OR, and NOT operators.
The AND and OR operators are used to filter records based on more than one condition:
The AND operator displays a record if all the conditions separated by AND are TRUE.
The OR operator displays a record if any of the conditions separated by OR is TRUE.
The NOT operator displays a record if the condition(s) is NOT TRUE.

# AND Syntax
SELECT column1, column2, ...
  FROM table_name
   WHERE condition1 AND condition2 AND condition3 ...;

# OR Syntax
SELECT column1, column2, ...
  FROM table_name
    WHERE condition1 OR condition2 OR condition3 ...;

# NOT Syntax
SELECT column1, column2, ...
  FROM table_name
    WHERE NOT condition;








