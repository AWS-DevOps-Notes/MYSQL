## MYSQL

* It is structured query language(SQL), which can we easily manipulate and retrive data.
* By using mysql we can provide acces particular person.

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

### 7 Different Types of Constraints in SQL

1) **`NOT NULL Constraint`**  (Ensures a column cannot have a null (empty) value.)
2) **`UNIQUE Constraint`** ( Ensures all values in a column are different.)
3) **`PRIMARY KEY Constraint`** (Ensures each record in a table is unique and not null.)
4) **`FOREIGN KEY Constraint`** (Links one table to another, enforcing valid relationships.)
5) **`CHECK Constraint`** (Ensures data meets a specific condition before being added to a column.)
6) **`DEFAULT Constraint`** (Sets a default value for a column if no value is provided.)
7) **`CREATE INDEX Constraint`**  (this constraint is used to make it easier for a database system to quickly retrieve data)
