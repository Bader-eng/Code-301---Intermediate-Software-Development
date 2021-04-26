## What is SQL?
* SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, 
and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage 
for millions of websites and mobile applications.

## Relational databases:
* Before learning the SQL syntax, it's important to have a model for what a relational database actually is. A relational database represents a collection of related 
 (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table)
  and any number of rows of data.
  
  ## SELECT queries 101:
  * To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries. A query in itself is just 
   a statement which declares what data we are looking for, where to find it in the database, and optionally, how to transform it before it is returned. 
   It has a specific syntax though, which is what we are going to learn in the following exercises.
  
  ## Queries with constraints (Pt. 1) :
  * we need to use a WHERE clause in the query. The clause is applied to each row of data by checking specific column values to determine whether
  it should be included in the results or not.
  
  ##  Queries with constraints (Pt. 2) :
  * When writing WHERE clauses with columns containing text data, SQL supports a number of useful operators to do things like case-insensitive 
  string comparison and wildcard pattern matching.
