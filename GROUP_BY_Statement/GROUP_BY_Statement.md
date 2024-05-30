## GROUP BY Statement


GROUP BY Statement allow us to aggregate columns per some category.


Let's explore this idea

    ```SELECT category_col, AGG(data_col) 
    FROM table 
    WHERE category_col !='A'
    GROUP BY category_col```

The GROUP BY clause must be appear right after a FROM or WHERE satement.



<!-- Add the second part of the group by statement -->

