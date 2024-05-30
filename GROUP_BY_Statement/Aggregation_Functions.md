## Aggregation Functions in SQL]


SQL provides us a variaty of aggeragate functions.

The main idea behind an aggeragate function is to take multiple inputs and return a single output.


### Most common aggeragate functions:
    - AVG() - returns average value
    - COUNT() - returns number of values
    - MAX() - returns maximum value
    - MIN() - returns minimum value
    - SUM() - returns the sum of all values


Aggregate function calls happen only in the SELECT clause or the HAVING clause.


Let's get over to the pgadmin and try some query

    1. `SELECT MIN(replacement_cost) FROM film;`
    2. `SELECT MAX(repalcement_cost) FROM film;`
    3. `SELECT COUNT(8) FROM film;`
    4. `SELECT AVG(replacement_cost) FROM film;`
    5. `SELECT SUM(replacement_cost) FROM film;`



Our next lesson will be on the GROUP BY. Go there and check that out ;)