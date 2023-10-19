### film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

```
    select count(*) from film where length > (select avg(length) from film)
```


### film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```
select count(*) from film where rental_rate = any (select max(rental_rate) from film)
```

### film tablosunda en düşük rental_rate ve en düşük replacement_cost değerlerine sahip filmleri sıralayınız.
```
select * from film where rentalrate =(select min(rental_rate) from film)
union all
select * from film where replacement_cost =(select min(replacement_cost) from film) 
```

### payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

```
SELECT customer.name payment.amount 
FROM customer INNER JOIN payment
ON customer.customer_id = payment.customer_id
WHERE amount =(SELECT MAX(amount)FROM payment)
```