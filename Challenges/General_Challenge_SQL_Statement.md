## Overview

General challenge tasks utilizing all the skills you have learned so far!

Note: Challenges are going to be a bit difficult, so try breaking down the problem into individual tasks!


The challenge structure is as follows:

    - Hints to the challenge
    - Solution to the challenge

## Challenge 01

How many payment transactions were greater than $5.00?


### Hints

- You will need to use the payment table
- You will also need to use COUNT and WHERE along with some comparison operator


### Solution(Challenge 01)

``SELECT COUNT(amount) FROM, payment WHERE amount > 5;``




## Challenge 02

How many actors have a first name that starts with the letter P?


### Hints


- You will need to use the actor table
- You will also need to use LIKE and a Wildcard operator, such as % or _


### Solution(02)

``SELECT COUNT(*) FROM actor WHERE first_name LIKE 'P%';``


## Challenge 03

How many unique districts are our customers from?


## Hints

- You will need to use the address table
- You will also need to use the COUNT and DISTINCT


### Solution(Challenge 03)

``SELECT COUNT(DISTINCT(district)) FROM address;``


## Challenge 04


Retrieve the list of names for those distinct district from the previous question.


### Hints

- You will again need to use the address table
- This will be very similar to the previous challenge


### Solution(Challenge 04)

``SELECT DISTINCT(district) FROM address;``



## Challenge 05

How many films have a rating of R and a replacement cost between $5 and $15?


### Hints


- You will need to use the film table
- You may also need to use BETWEEN and a WHERE statement with a comparison operator.


### Solution(Challenge 05)

``SELECT COUNT(*) FROM film WHERE rating = 'R' AND replacement_cost BETWEEN 5 AND 15;``



## Challenege 06


How many films have the word Truman somewhere in the title?


### Hints


- You will need to use the film table
- You will also need to use LIKE and a wildcard operator

### Solution(Challenge 06)


``SELECT COUNT(*) FROM WHERE title LIKE '%Truman%'``


Move the solutions to the solutions folder!!