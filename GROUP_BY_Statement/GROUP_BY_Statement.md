## GROUP BY Statement


GROUP BY Statement allow us to aggregate columns per some category.


Let's explore this idea

    ```SELECT category_col, AGG(data_col) 
    FROM table 
    WHERE category_col !='A'
    GROUP BY category_col```

The GROUP BY clause must be appear right after a FROM or WHERE satement.



Here are some of the query's that you can perform in the pgadmin:

    1.  ```SELECT customer_id FROM payment GROUP BY customer_id;```
    2. ``SELECT customer_id, SUM(amount) FROM payment GROUP BY customer_id ORDER BY SUM(amount) DESC;```
    3. ```SELECT staff_id, customer_id, SUM(amount) FROM payment GROUP BY staff_id, customer_id ORDER BY staff_id, customer_id;``` 
    4. ```SELECT DATE(payment_date), SUM(amount) FROM payment GROUP BY DATE(payment_date) ORDER BY SUM(amount) DESC;```


Cool! That's all about GROUP BY statement. Next thing is there is a challenge reagrding the GROUP BY statement, go ahead and check that out ;)

