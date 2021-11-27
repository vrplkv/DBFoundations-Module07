Name: Vera Poliakova

Date: November 26, 2021

Course: IT FDN 130 A

# Assignment 7–Functions
## Introduction
This document will explain the differences between Scalar, Inline, Multi-Statement Functions and when to use a SQL UDF.
### Scalar
A Scalar Functions takes parameters, executes the code, and returns a single value. Generally, these are used to do perform calculations. 
### Inline
An Inline function is similar to a view which returns a table from a single select statement. Unlike a table parameters can be used. 
### Multi-Statement
A Multi-Statement function can return a table built from multiple select statements and from various sources. This is useful to execute multiple queries and aggregate results into the returned table of the function. 
### User Defined Function (UDF)
SQL has built in functions, or user defined function (UDF) can be created to perform an action. These functions are stored in the database and can be called elsewhere in the SQL code to perform the desired action. This is useful for created complex calculations or tables. 
## Conclusion
This document discussed different types of functions in SQL, including scalar, inline, multi-statement and user defined. 
