## MYSQL

* It is structured query language(SQL), which can we easily manipulate and retrive data.
* By using mysql we can provide acces particular person.

## What is a Database?

* Database is a collection of data elements.
* A relational database is collection of related data elements stored in the form of tables(rows and columns)

## RDBMS:

* A relational database management system (RDBMS) is a program used to create, update, and manage relational databases.
* Relation means between any database or tables.

## SQL Constraints:

* Constraints in SQL are used to define rules for data stored in a table. 
* They help maintain accuracy, integrity, and reliability by limiting what type of data can be entered into the table. 

### Syntax:  

```
CREATE TABLE table_name (
    column1 datatype constraint,
    column2 datatype constraint,
    column3 datatype constraint,
    ....
);
```

### 7 Different Types of Constraints in SQL [Referhere](https://www.digitalocean.com/community/tutorials/sql-data-types)

1) **`NOT NULL Constraint`**  (Ensures a column cannot have a null (empty) value.)
2) **`UNIQUE Constraint`** ( Ensures all values in a column are different.)
3) **`PRIMARY KEY Constraint`** (Ensures each record in a table is unique and not null.)
4) **`FOREIGN KEY Constraint`** (Links one table to another, enforcing valid relationships.)
5) **`CHECK Constraint`** (Ensures data meets a specific condition before being added to a column.)
6) **`DEFAULT Constraint`** (Sets a default value for a column if no value is provided.)
7) **`CREATE INDEX Constraint`**  (this constraint is used to make it easier for a database system to quickly retrieve data)

The following constraints are commonly used in SQL:

* `NOT NULL` - Ensures that a column cannot have a NULL value

* `UNIQUE` - Ensures that all values in a column are different
* `PRIMARY KEY` - A combination of a NOT NULL and UNIQUE. Uniquely identifies each row in a table
* `FOREIGN KEY` - Prevents actions that would destroy links between tables
* `CHECK` - Ensures that the values in a column satisfies a specific condition
* `DEFAULT` - Sets a default value for a column if no value is specified
* `CREATE INDEX` - Used to create and retrieve data from the database very quickly

### SQL data types can be broadly divided into the following categories.

1) `Numeric data types` 
    * INT, TINYINT, BIGINT, FLOAT, REAL, etc.
2) `Date and Time data types` 
    * DATE, TIME, DATETIME, etc.
3) `Character and String data types` 
    * CHAR, VARCHAR, TEXT, etc.
4) `Unicode character string data types` 
    * NCHAR, NVARCHAR, NTEXT, etc.
5) `Binary data types` 
    * BINARY, VARBINARY, etc.
6) `Miscellaneous data types`
    * CLOB, BLOB, XML, CURSOR, TABLE, etc.


### Ascending Order in sql:

* The **`ORDER BY`** keyword sorts the records in `ascending order` by default. 
* To sort the records in `descending order`, use the **`DESC`** keyword.

* To use ascending and descending at a time, use order by
    ```sql
    SELECT * FROM table_name ORDER BY column1 ASC, column2 DESC;
    ```
## To clear sql screen

**command**: `\! cls`






