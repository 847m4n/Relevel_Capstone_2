**THIS FILE CONTAINS ALL THE QUESTIONS AND THE QUERIES**

PROBLEM STATEMENT 1 : How many customers has Foodie-Fi ever had?

QUERY :

SELECT
 COUNT(DISTINCT customer_id) AS unique_customer
FROM dbo.subscriptions;
