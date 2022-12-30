SELECT t1.name, t2.category, SUM(t1.sales) as total_sales
FROM table1 t1
INNER JOIN table2 t2 ON t1.id = t2.id
WHERE t1.date >= '2022-01-01' AND t1.date < '2022-12-31'
GROUP BY t1.name, t2.category
HAVING total_sales > 1000
ORDER BY total_sales DESC
