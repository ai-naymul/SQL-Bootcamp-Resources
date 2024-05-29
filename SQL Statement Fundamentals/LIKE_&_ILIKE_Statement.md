## LIKE & ILIKE Statement

We have already been able to perform direct comparison against strings, such as:
    
    - WHERE first_name='John'

But what if we want to match against a general pattern in a string?
    - All emails ending in '@gmail.com'
    - All names that begin with an 'A

The LIKE operator allows us to perform pattern matching against string data with the use of wildcard characters:
    - Percent(%)
        - Matches any sequence of characters
    - Underscore(_)
        - Matches any single character

All names that begin with an 'A
    - WHERE name LIKE 'A%'

All names that end with a
    - WHERE name LIKE '%a'

Notice that LIKE is case-sensitive, we can use ILIKE which is case-sensitive.

Using the underscore allows us to replace just a single character
    - Get all mission impossible films
    - WHERE title LIKE 'Mission Impossible_'


You can use underscores, Imagine we had version string codes in the format 'Version#A4', 'Version#B7', etc...
    - WHERE value LIKE 'Version#__'


We can also combine pattern matching operators to create more complex patterns
    -WHERE name LIKE '_her%'

Here are some of the query you can perform in the pgadmin:

1. `SELECT * FROM customer WHERE first_name ILIKE '%j' AND last_name ILIKE 'j%'`

2. `SELECT * FROM cusomer WHERE first_name LIKE 'A%' AND last_name NOT LIKE 'B%' ORDER BY last_name`.


These all about SQL statement fundamentals, There is general challenge waiting for you. Go ahead and check that out Thanks ;)