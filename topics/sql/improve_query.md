## Comparisons vs. Functions

1. Improve the following query

```
SELECT count(*)
FROM shawarma_purchases
WHERE
  YEAR(purchased_at) == '2017'
```

SELECT COUNT(*)
FROM shawarma_purchases
WHERE YEAR(purchased_at) = 2017;

or

SELECT COUNT(*)
FROM shawarma_purchases
WHERE purchased_at >= '2017-01-01' AND purchased_at < '2018-01-01';

