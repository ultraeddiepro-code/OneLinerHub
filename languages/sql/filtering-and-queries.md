CASE WHEN col > 100
THEN 'High'
ELSE 'Low'
END

WHERE col IN
(SELECT col FROM table)

WITH cte AS (...)