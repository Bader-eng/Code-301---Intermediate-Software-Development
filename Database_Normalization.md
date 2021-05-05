## Database normalization :
* is a process used to organize a database into tables and columns. The idea is that a table should be about a 
specific topic and that only those columns which support that topic are included.

## hree main reasons to normalize a database:
1. The first is to minimize duplicate data
2. he second is to minimize or avoid data modification issues
3. simplify queries

## Duplicated information presents two problems:
1. It increases storage and decreases performance.
2. it becomes more difficult to maintain data changes.


## There are three common forms of normalization:

1. First Normal Form – The information is stored in a relational table and each column
contains atomic values, and there are not repeating groups of columns.
2. Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
3. Third Normal Form – The table is in second normal form and all of its columns are not transitively dependent on the primary key.
