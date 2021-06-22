# SQL Server

## Foreign/Primary Keys
Database -> <Table-name> -> Keys
  
SQL Server Management Studio (SSMS) by default names new foreign keys in following way:

**FK_Mytable_Othertable**

where **Mytable** is a table that holds foreign key and **Othertable** is the primary key table.

## Stored Procedures

Stores procedures should always be prefixed with "sp_" and executed with a prefix of "sys.", i.e. sys.sp_exampleSp.
Stored procedures are found in the Tables -> Programmability -> Stored Procedures folder.

## Index

You typically want to use an index, especially if you are performing a lot of deletes. Adding a nonclustered index on the column
by which you are deleting can improve performance ALOT. However, it will slow down inserts since the database now have to store the
data necessary for the index every time something new is inserted into the DB.

## Task Scheduler

Here is where you would place Batch jobs that you want to run on a recurring basis.

## SQL Profiler
Useful for seeing the SQL traffic locally!
