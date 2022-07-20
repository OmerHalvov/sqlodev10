# sqlodev10
Patika SQL Ödev-10

Cevap-1:
SELECT country, city FROM country
LEFT JOIN city ON city.country_id = city.country_id;

Cevap-2:
SELECT first_name, last_name, payment_id FROM payment
RIGHT JOIN customer ON payment.customer_id = customer.id

Cevap-3:
SELECT rental_id, first_name, last_name FROM rental
FULL JOIN customer ON rental_id = customer.customer_id;
