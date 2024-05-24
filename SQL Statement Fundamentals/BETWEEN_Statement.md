## BETWEEN Statement

The BEWTEEN statement operator can be used to match value against a range of values.

Sample:
    value BETWEEN low AND high

The between operator is the same as:
    1. value >= low AND <= high
    2. value BETWEEN low and high

you can also conbine BEWTEEN with the  NOT logical operator:

value NOT BETWEEN low and high

BETWEEN operator also can be used with dates.Note that you need to format dates in the ISO 8601 format,
which is like YYYY-MM-DD.

For example:
    * date BEWTEEN '2007-01-01' AND '2007-02-01'

When using BEWTEEN opertator with dates that also include timestamp information pay carefull attention to using BETWEEN versus <=, >= comparison operators, due to the fact that a datetime starts at 0:00.


Let's get our hand dirty on pgadmin -

    1. `SELECT * FROM payment WHERE amount BETWEEN 8 AND`
    2. `SELECT * FROM payment WHERE payment_date BETWEEN ''2007-02-01' AND '2007-02-14'`

Our next lesson is on IN statement.Goahead and check that out.