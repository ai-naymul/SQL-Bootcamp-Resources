## SELECT DISTINCT Statement

Sometimes a table contains a column that has a duplicated values, and you may find yourself in a situation where you only want to list the unique/distinct values.

The `DISTINCT` keyword can be used to return the distinct value in the column.

The syntax for using the DISTINCT keyword is:

```SELECT DISTINCT column_name FROM table_name;```

you can also use the parenthesis for the DISTINCT keyword like the following:

```SELECT DISTINCT(column_name) FROM table_name;```

Both works either way.

Some of the query you can run using the DISTINCT for our dvd rental database:

1. ```SELECT DISTINCT(rental_rate) FROM film;```

Its gives the unique values that are available in the rental_rate column in the film table.

2. ```SELECT DISTINCT(realease_year) FROM film;```

Its gives the unique values that are available in the realease_year column in the film table.

We got you a challenge for this lesson also.Try to make some query on your own to get the concept well then move forward to the challenge to get your hand more dirty.Les goo.