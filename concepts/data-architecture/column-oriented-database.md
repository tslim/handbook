# Column Oriented Database

A column-oriented DBMS (or columnar database management system) is a [[database]] management system (DBMS) that stores data tables by column rather than by row. Practical use of a column store versus a row store differs little in the relational DBMS world. Both columnar and row databases can use traditional database query languages like SQL to load data and perform queries. Both row and columnar databases can become the backbone in a system to serve data for common extract, transform, load ([[etl]]) and [[data-visualization]] tools. However, by storing data in columns rather than rows, the database can more precisely access the data it needs to answer a query rather than scanning and discarding unwanted data in rows.

## Examples

- [ClickHouse](https://github.com/ClickHouse/ClickHouse/)

[//begin]: # "Autogenerated link references for markdown compatibility"
[database]: database "Database"
[etl]: etl "Extract, transform, load"
[data-visualization]: data-visualization "Data Visualization"
[//end]: # "Autogenerated link references"