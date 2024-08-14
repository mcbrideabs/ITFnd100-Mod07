# ITFnd100-Mod07
Module 7 Repository and Page
#### Name: Abigail McBride
#### Date: 08.13.2024
#### Course: ITFnd 130A

# Assignment 07 - Functions

## Introduction 

This paper will explore when one would use a SQL User Defined Function (UDF), and explain the differences between Scalar, Inline, and Multi-Statement Functions.


## UDFs and Scalar, Inline, and Multi-Statement Functions

User Defined Functions are used most often to create robust functions that go beyond SQL’s basic, built-in functions. They can be made to return a table of values or 
a singular value. UDFs can be made through custom combinations of functions and commands to define data in the way the user wants. Of UDFs, Scalar functions are the 
most simple and will return a single value as an expression. Scalar UDFs can be used to check constraints put on a table or execute simple expressions and require schemas 
to be defined. Inline UDFs will return a table as the result instead of a single value. This Inline table can be used in other commands and queries like a view can, unlike 
Scalar results. Whereas Inline table functions work similarly to a view that has parameters, a Multi-Statement Function can work just as a regular table will. Multi-Statement 
Functions are UDFs which utilize the ‘returns table’ command, which differs from the singular select statement used in Inline UDFs. When the ‘returns table’ command is 
used the code afterwards defines what will populate that table.

## Summary
This paper explains when a SQL UDF is used, and the differences between Scalar, Inline, and Multi-Statement Functions. UDFs are a versatile tool of which Scalar 
UDFs are the most simplistic. Inline UDFs can be used to return a structured table of results, but it functions within parameters; Multi-Statement Functions are 
the most robust in that they can return a normal table as a result and utilizes the ‘returns table’ command to permit more complex code to populate the defined 
table as compared to a singular ‘select’ statement.
