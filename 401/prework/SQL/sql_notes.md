# SQL | Relational Databases

Relational databases are very useful when various tables have shared schema properties.

Each table can be thought of as a 2D entity consisting of rows and columns. 

We can use conditional statements/constraints to get specific entries within the database such as `=`, `!=`, `<=`, etc

We can also limit the amount of data being returned (e.g. only returning the first 5 rows of data) and also offset the data (e.g. returning the first 5 rows starting at row 100)

Select queries typically follow this format:

```
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset;
```

Although the "where", "order by", "limit", and "offset" conditions are not mandatory to make a query.

We can also query multiple tables at once and join them together as a single table of returned values using 'INNER JOIN'

```
SELECT column, another_table_column, …
FROM mytable
INNER JOIN another_table 
    ON mytable.id = another_table.id
WHERE condition(s)
ORDER BY column, … ASC/DESC
LIMIT num_limit OFFSET num_offset;
```

We can also Insert, Update, and Delete the rows within a table, as well as Create, Delete, and Alter (add new columns, remove column, rename tables) whole tables as well.

___

# Screenshot Proof of Completion

![Tutorial 1](https://kmartwork.github.io/reading-notes/SQL/sql_1.JPG)
![Tutorial 2](https://kmartwork.github.io/reading-notes/SQL/sql_2.JPG)
![Tutorial 3](https://kmartwork.github.io/reading-notes/SQL/sql_3.JPG)
![Tutorial 4](https://kmartwork.github.io/reading-notes/SQL/sql_4.JPG)
![Tutorial 5](https://kmartwork.github.io/reading-notes/SQL/sql_5.JPG)
![Tutorial 6](https://kmartwork.github.io/reading-notes/SQL/sql_6.JPG)
![Tutorial 13](https://kmartwork.github.io/reading-notes/SQL/sql_13.JPG)
![Tutorial 14](https://kmartwork.github.io/reading-notes/SQL/sql_14.JPG)
![Tutorial 15](https://kmartwork.github.io/reading-notes/SQL/sql_15.JPG)
![Tutorial 16](https://kmartwork.github.io/reading-notes/SQL/sql_16.JPG)
![Tutorial 17](https://kmartwork.github.io/reading-notes/SQL/sql_17.JPG)
![Tutorial 18](https://kmartwork.github.io/reading-notes/SQL/sql_18.JPG)
