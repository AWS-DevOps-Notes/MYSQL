### Query:

![preview](images/sql4.png)

### How to connect to MySQL:

**Syntax**
```
$ mysql –u <user_name> -p
Enter password: <password>
```
### How to display all available databases?

**Syntax**:
```
mysql> SHOW DATABASES;
```
### How to create a new database?

**Syntax**:
```
mysql> CREATE DATABASE <database_name>;
```

### How to connect to a particular database?

**Syntax**:

```
mysql> USE <database_name>; OR
mysql> CONNECT <database_name>;
```
### Know which database user is connected

**Syntax**:
```
mysql> SELECT DATABASE() ;
```
### Display tables available in Database?

**Syntax**:
```
mysql> SHOW TABLES;
```

**`INSERT`**:

**Syntax**: INSERT INTO <table_Name> VALUES <(List of values for a row separated by
commas)>;

* Ex: Insert the following data into LOCATION table:
    Location Number(lCode) = 122 
    Location Name(lName) = Chicago

```
INSERT INTO Location VALUES(122, ‘Chicago’);
```


