# Database Normalization
## Database normalization : is a process used to organize a database into tables and columns. The idea is that a table should be about a specific topic and that only those columns which support that topic are included.

## By limiting a table to one purpose, you reduce the number of duplicate data that is contained within your database, which helps eliminate some issues stemming from database modifications. 

## KEY: is a value used to identify a record in a table uniquely. A KEY could be a single column or combination of multiple columns

## There are three main reasons to normalize a database:
1. ### To minimize duplicate data
2. ### To minimize or avoid data modification issues
3. ### To simplify queries

## There are three common forms of normalization: 1st, 2nd, and 3rd normal form. 

### First Normal Form – The information is stored in a relational table and each column contains atomic values, and there are not repeating groups of columns.
### Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
### Third Normal Form – The table is in second normal form and all of its columns are not transitively dependent on the primary key.
