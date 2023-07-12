# sql_questions

1. What are Entities and Relationships

In SQL, an entity is a table or view in a database that represents a real-world object or concept. For example, a customer or an order. An entity is defined by its attributes, which are the characteristics of the entity. Attributes are columns in the table that store data about the entity. Relationships in SQL are used to associate entities with one another. A relationship is defined as a connection between two or more entities. There are different types of relationships in SQL such as one-to-one, one-to-many, many-to-one and many-to-many. 

2. Write a SQL query to delete a table from the database and memory while keeping the structure of the 
table intact?

TRUNCATE TABLE table_name;

3. What is the difference between primary key and unique key?

A primary key is a column or a set of columns that uniquely identifies each row in a table. It cannot contain null values and must be unique. A table can have only one primary key. A unique key is a constraint that ensures that all values in a column are unique. Unlike the primary key, it can contain null values

4. What are the subsets of SQL?

DDL – Data Definition Language
DQl – Data Query Language
DML – Data Manipulation Language
DCL – Data Control Language

5. A table named 123_A is created for storing the number of employees in an organization. What is 
wrong in the name of the table?

the table has to start with letter or underscore.

6. How do I rename a column?

in the gui of ssms when you open the database folder