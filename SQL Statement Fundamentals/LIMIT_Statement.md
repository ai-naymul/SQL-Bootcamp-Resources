## LIMIT Statement

The LIMIT clause helps us to limit the number of rows that return from a query.
Usefull to use when you don't wanna shows a lot of rows. 
Its great when you use it with the ORDER BY clause.

LIMIT goes at the end of the query request and is the last command to be executed.

Here are some of the query you can perform to our database:

1. `SELECT * FROM payment ORDER BY payment_date DESC LIMIT 5;`

2. `SELECT * FROM payment WHERE amount != 0.00 ORDER BY payment_date DESC LIMIT 5;`

3. `SELECT * FROM payment LIMIT 1;`

Next thing is there is challenge out there using the ORDER BY and the LIMIT clause together, Go check that out.