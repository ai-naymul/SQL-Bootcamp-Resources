## IN Statement

In certain case you want to check for multiple possible options, for example, if a user's name shows up IN a list of known names. 

We can use the IN operator to create a condition that checks to see if a value in included in a list multiple options.

The general syntax of the IN statement is:

    * value IN (option1, option2,..., optionn)


Example query:

    `SELECT color FROM table WHERE color NOT IN ('red', 'blue')`


Let's get our hands dirty on pgadmin:

    1. `SELECT * FROM payment WHERE amount IN (0.99,1.98,1.99)`
    2. `SELECT * FROM payment WHERE amount NOT IN (0.99,1.98,1.99)`


Our next lesson will be on LIKE and ILIKE statement. Go ahead and check that out ;)