## Select Where Statment

SELECT and WHERE are the most fundamental SQL statement that you will gonna use most of the time.

The WHERE statment specify conditions on columns for the row to be returend.

Basic syntax example:

```SELECT column_1,column_2 FROM table_name WHERE condition```

The WHERE clause appreantly came after the FROM clause of the SELECT statement.

The condition are used to filter the rows returned from the SELECT statement.

We are not covering the too basic stuff like operators.Regarding the operator, please have a search on google about comparision and logical operator you could have a great explaination about this topic there.

Here are some query you can perform into our database:

1. ```SELECT * FROM customer WHERE first_name = 'Jared'; ```

2. ```SELECT * FROM film WHERE rental_rate > 4;```

3. ```SELECT * FROM film WHERE rental_rate > 4 AND replacement_cost >= 19.99;```

4. ```SELECT COUNT(*) FROM film WHERE rating = 'R' OR rating = 'PG-13'; ```

This all about SELECT WHERE statement.There is a challenge waitng for you in the challenges folder, please check that out and complete the challenge.