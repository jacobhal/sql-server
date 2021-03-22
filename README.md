# SQL Server

## Foreign/Primary Keys
Database -> <Table-name> -> Keys
  
SQL Server Management Studio (SSMS) by default names new foreign keys in following way:

**FK_Mytable_Othertable**

where **Mytable** is a table that holds foreign key and **Othertable** is the primary key table.

## Stored Procedures

Stores procedures should always be prefixed with "sp_" and executed with a prefix of "sys.", i.e. sys.sp_exampleSp.
Stored procedures are found in the Tables -> Programmability -> Stored Procedures folder.
## SQL Profiler
Useful for seeing the SQL traffic locally!
