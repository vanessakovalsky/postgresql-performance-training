# Requete SQL : 

* Première requête : 
```sql 
select b.first_name,b.last_name,a.title 
from film a,actor b, film_actor c 
where   c.film_id=a.film_id 
and c.actor_id=b.actor_id
order by b.first_name,b.last_name
```
* Deuxième requete
```

```

* Troisière requête :
```
SELECT * FROM rental WHERE customer_id IN ( SELECT customer_id FROM customer WHERE address_id IN (SELECT address_id FROM address WHERE district = 'Texas'))  
```
ou
```
    SELECT FILM.*
    FROM FILM, INVENTORY, RENTAL, CUSTOMER, ADDRESS 
    WHERE FILM.film_id = INVENTORY.film_id
    AND INVENTORY.inventory_id = RENTAL.inventory_id
    AND RENTAL.customer_id = CUSTOMER.customer_id
    AND CUSTOMER.address_id = ADDRESS.address_id
    AND ADDRESS.district = 'Texas'
```

