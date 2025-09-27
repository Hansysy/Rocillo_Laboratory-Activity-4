# Rocillo_Laboratory-Activity-4

# JOIN QUERIES
INNER JOIN
Combines two tables and only shows rows where there is a match in both.

LEFT JOIN
Shows all rows from the left table and adds matching rows from the right table; if no match, the right side shows NULL.

RIGHT JOIN
Shows all rows from the right table and adds matching rows from the left table; if no match, the left side shows NULL.

FULL JOIN (FULL OUTER JOIN)
Returns all rows from both tables, with NULL where no match exists (MySQL emulates this using LEFT JOIN UNION RIGHT JOIN).

CROSS JOIN
Pairs every row from the first table with every row from the second table, making all possible combinations.

SELF JOIN
Joins a table to itself (using aliases) to show relationships within the same table.

LEFT JOIN with Subquery
Shows all rows from the left table and attaches only the latest (or filtered) result from a subquery; if none exists, shows NULL.

# END POINTS
