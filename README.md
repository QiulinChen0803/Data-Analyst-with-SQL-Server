# Data-Analyst-with-SQL-Server

[Data Analyst with SQL Server](https://learn.datacamp.com/career-tracks/data-analyst-with-sql-server?version=2) @ [DataCamp](https://learn.datacamp.com/)

## Topics Covered
### Course 1: Introduction to SQL Server
- Selecting one or more columns with SELECT, Ordering results with ORDER BY, and Filtering results using WHERE and HAVING clauses
- Aggregating and summarising using SUM, COUNT, MIN, MAX and AVG, and Text manipulation with LEFT, RIGHT, LEN and SUBSTRING
- GROUP BY for splitting results into groups of interest Basic Joins - using INNER, LEFT and RIGHT joins
- Combining data from different tables with UNION and UNION all
- Transforming data using CASE statements
- Creating tables, and inserting, updating and deleting records
- Creating and using variables for more efficient queries, and creating temporary tables

### Course 2: Introduction to Relational Databases in SQL
- Transformed data sets step by step into the database schema on the right – only by executing SQL queries
- Defined column data types, added primary keys and foreign keys
- Specified relationships between tables to guarantee better data consistency and therefore quality

### Course 3: Intermediate SQL Server

### Course 4: Time Series Analysis in SQL Server
- Used date functions and also combine DATEADD() with DATEDIFF() to round off to the nearest minute or hour
- Learned how to use CAST(), CONVERT(), and FORMAT() to turn dates into strings for reporting
- FORMAT() can be an order of magnitude slower than the others
- Calendar tables
- Converted strings into dates by CAST(), CONVERT(), and PARSE() functions, even when the string uses a different locale
- TRY_CAST(), TRY_CONVERT(), and TRY_PARSE() are just as fast and are also type-safe: NULL value instead of an error when the string does not parse to a date
- Learned how SQL Server keep track of time zones using offsets and how to translate dates between time zones and changing time zones altogether
- Reviewed aggregation functions like COUNT(), MIN(), MAX(), etc.
- Reviewed statistical aggregate functions like AVG(), STDEV(), and VAR()
- Aggregate data using ROLLUP, CUBE, and GROUPING SETS
- Time series problems: window functions are, both for ranking functions like ROW_NUMBER() and RANK(), but also for aggregate functions like SUM() or AVG()
- Calculate running totals and moving averages over windows of data
- Learned how to look backward and forward in time with LAG() and LEAD(), respectively
- Learned how to calculate the maximum level of overlap, important for discovering concurrency in data sets

### Course 5: Functions for Manipulating Data in SQL Server
- The most important data types supplied by SQL Server: Choosing the appropriate type for columns, variable or expression can make a big difference in the performance of the queries. There are three major categories of data types: numeric, date and time and characters. Data conversion was another topic. In some cases, this is done behind the scenes, by SQL Server and it is called implicit conversion. Other times, we need to explicitly convert your data.

- The most important date and time functions: functions that return date and time information from the operating system. The most commonly used is GETDATE(). The functions returning parts of a date are also important. Some examples are: YEAR(), MONTH(), and DAY(). Then, we learned how to perform arithmetic operations on dates, using DATEADD() and DATEDIFF(). And you also know how to validate if an expression is a date.

- Manipulating strings: the functions that look for an expression within an string and return its position. CHARINDEX() and PATINDEX() were discussed. 
- Transforming the appearance of a string with functions like UPPER(), LOWER(), LEFT(), and RIGHT(); apply functions on groups of strings. It is now easy to create a string from parts or to break one into pieces by using built-in functions provided by SQL Server: STRING_AGG() and STRING_SPLIT().

- Recognizing numeric data properties: aggregate data in your queries with SUM(), MIN(), MAX(), and AVG(). With the analytic functions, we can easily perform calculations on subsets of rows and retrieve them in your queries, without the need to use the 'GROUP BY' clause. These are: FIRST_VALUE(), LAST_VALUE(), LAG() and LEAD(). There are built-in functions for performing mathematical operations as well.

### Course 6: Database Design

### Course 7: Transactions and Error Handling in SQL Server
- Studied how to handle errors in SQL Server; Learned how to use the TRY...CATCH construct; Analyzed the anatomy of the errors, explaining each part of them; Saw there are some errors that a CATCH block can't catch.
- Used some functions that give us information about errors, such as ERROR_NUMBER(), ERROR_SEVERITY(), ERROR_STATE(), ERROR_LINE(), ERROR_PROCEDURE(), and ERROR_MESSAGE().
- Demonstrated how to raise errors using RAISERROR and THROW, and saw the differences between both of them.
- Explained the concept of transactions, and learned how to use the transaction statements, BEGIN TRAN, COMMIT TRAN, and ROLLBACK TRAN.
- Practiced with the @@TRANCOUNT function, and with savepoints.
- Controlled the errors in transactions with the use of XACT_ABORT and XACT_STATE.
- Clarified the concept of concurrency; Explained the different isolation levels that SQL Server provides: READ UNCOMMITTED, READ COMMITTED, REPEATABLE READ, SERIALIZABLE and, SNAPSHOT; Learned the differences between them and whether they prevent some concurrency phenomena such as dirty reads, non-repeatable reads, and phantom reads.

### Course 8: Writing Functions and Stored Procedures in SQL Server

### Course 9: Building and Optimizing Triggers in SQL Server

### Course 10: Improving Query Performance in SQL Server
