What is SQL injection?

SQL injection is one of the most common web hacking techniques. It's a code injection technique that might destroy your database.

What are 3 methods SQL injection can be done by?

SELECT *
FROM customers
WHERE customer_id = '1234567'

1234567; DELETE * customers WHERE '1' = '1

SELECT *
FROM customers
WHERE customer_id = '1234567';
DELETE *
FROM customers
WHERE 'x' = 'x'

How can we detect and sanitize SQL injection attacks?

You can utilize Intrusion detection systems (IDS), both network- and host-based, so it can be tuned to detect SQL injection attacks.
Also limiting account privileges assuming that something will slip past you.