# DBFoundations-Module07

Name: Salvador Gavonel

Date: November 29, 2021

Course: IT FDN 130 A

Assignment 07

Github URL: [https://github.com/Sgavon/DBFoundations-Module07](https://github.com/Sgavon/DBFoundations-Module07)

# SQL Views, Functions Continued
## Introduction:
Module 07 expands even further on Views, and Functions.  We look at the different uses of the built-in functions SQL houses as well as the uses of UDF, or User-Defined Functions, to create our own custom functions when we need to.
## When to use a ‘UDF’:
Sometimes the built-in functions that SQL provides are not enough to do what the user is wanting to do, routines that are not normal within the SQL code.  This is where UDF come in to allow users to customize their own procedure so that it can be reused whenever the user wants to.
User defined functions are useful when we need to view a table or get a return value based on parameters given to it.  Like views, UDFs can be called upon repeatedly, but the parameters that UDFs have give it additional versatility to calculate new values from one or multiple tables or return a single value back to the user from a table.  
## Differences and Similarities between Scalar, Inline and Multi-Statement Functions:
All functions have the purpose to return values or tables back to the user; Scalar, inline and multi-statement functions all have this similarity, the difference is how these are constructed and what they return back to the user.
	Scalar functions are functions that return a single value back to the user.  For example, if you have a function calculating the circumference of a circle, you can have solved for the circumference given the radius as a parameter to the function.
	In-line functions and multi-statement functions are similar in that they both return tables back to the user, but the structure of each of these functions are different.
	In-line functions have simpler code and are more similar to views in that it is comprised by a return select statement.  Multi-statement functions will have to define a temporary table first, and then the following statements will insert information into the table.  The multi-statement function allows the user to perform additional calculations/routines before inserting the information into the temporary table.
## Summary:
In this module we look at additional uses of view and functions to understand the amount of functionality we can get from when using them on simple tables such as the northwind database.  By inserting functions, we can transform and calculate all of the values stored in the database to view as we wish, without affecting the integrity of the database in any way. 
