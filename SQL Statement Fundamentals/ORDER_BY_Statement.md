## ORDER BY Statement 

You may have seen that sometimes postgresql returns same result in different order. You can use ORDER BY to sort rows based on a column value, in either ascending or descending order.

Basic syntax of ORDER BY clause:

`SELECT column_1, column_2 FROM FROM table_name ORDER BY ASC/DESC`

Here as you can see ORDER BY towards the end of a query, since we want to do any selection and filtering first, before finally sorting.

`SELECT column_1, column_2 FROM table_name ORDER BY column_1 ASC/DESC`

- Use ASC to sort in ascending order
- Use DESC to sort in descending order
- If you leave it blank, ORDER BY use its default ASC.


This order by clause can be used in multiple columns.This make sense while a column has duplicate columns.

Here are some of the query you can perform into our dvd rental database:

```SELECT * FROM customer ORDER BY first_name DESC```

```SELECT store_id, first_name, last_name FROM customer ORDER BY store_id DESC, first_name ASC```

The next clause will be LIMIT clause go ahead and check that out in the LIMIT Statement.