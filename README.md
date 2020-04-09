## Quiz: SQL

???

# SQL

?: SQL (Structured Query Language) is a language for what?

( ) Building classes ( ) Creating databases only ( ) Using SQLite only (X) Managing data in a database

?: If SQLite is installed, how can you find out which version you are using?

( ) `which sqlite` (X) `which sqlite3` ( ) `which sql` () All of the Above

?: To exit SQLite, which command can be used?

( ) `ctrl + c` ( ) `command + c` ( ) `exit` (X) `.quit`

?: To list all the tables in a database, which command is used?

( ) `.help` ( ) `.schema` (X) `.tables` ( ) `.list`

?: To look at the structure of a database, which command is used?

( ) `.help` (X) `.schema` ( ) `.tables` ( ) `.list`

?: To delete a table, which command is used?

( ) `DROP TABLE table_name` ( ) `DROP table_name;`  ( ) `DROP table_name` (X) `DROP TABLE table_name;`

?: To store data that will be represented as a whole number, which data type is used?

( ) REAL ( ) BLOB (X) INTEGER ( ) TEXT

?: To add a column to an existing table, which command is used?

(X) `ALTER TABLE table_name ADD COLUMN column_name TEXT;` ( ) `CHANGE TABLE table_name ADD COLUMN column_name TEXT;` ( ) `CHANGE TABLE table_name COLUMN column_name TEXT;` ( ) `ALTER TABLE table_name ADD COLUMN column_name TEXT`

?: To add data into an existing database table, which command is used?

( ) `ADD TO` (X) `INSERT INTO` ( ) `UPDATE` ( ) `INSERT`

?: To retrieve data from an existing database table, which command is used?

( ) `SELECT FROM` ( ) `FROM` ( ) `SELECT` (X) `SELECT * FROM`

?: Basic aggregate functions in SQL include:

( ) `average` ( ) `minimum` ( ) `count` (X) All of the Above

?:

```sql
band             most_hated_rank    genre             country
---------------  ----------------   ----------------  ----------
Nickelback        1                 alternative rock  Canada
Creed             2                 alternative metal US
Limp Bizkit       3                 rap rock          US
Coldplay          4                 pop               England
```

```sql
SELECT * FROM band ORDER BY(most_hated_rank) DESC LIMIT 2;
```

What will the SQL query above return?

( )
```sql
band             most_hated_rank    genre             country
---------------  ----------------   ----------------  ----------
Coldplay          4                 pop               England
```
( )
```sql
band             most_hated_rank    genre             country
---------------  ----------------   ----------------  ----------
Nickelback        1                 alternative rock  Canada
```
( )
```sql
band             most_hated_rank    genre             country
---------------  ----------------   ----------------  ----------
Nickelback        1                 alternative rock  Canada
Creed             2                 alternative metal US
```
(X)
```sql
band             most_hated_rank    genre             country
---------------  ----------------   ----------------  ----------
Coldplay          4                 pop               England
Limp Bizkit       3                 rap rock          US
```

???
