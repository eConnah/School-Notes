**SELECT**: The SELECT statement is used to retrieve data from a database.

```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```

**INSERT**: The INSERT statement is used to add new data to a database.

```sql
INSERT INTO table_name (column1, column2, ...)
VALUES (value1, value2, ...);
```

**UPDATE**: The UPDATE statement is used to modify existing data in a database.

```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

**DELETE**: The DELETE statement is used to delete data from a database.

```sql
DELETE FROM table_name
WHERE condition;
```

**CREATE TABLE**: The CREATE TABLE statement is used to create a new table in a database.

```sql
CREATE TABLE table_name (
    column1 datatype1,
    column2 datatype2,
    ...
);
```

**DROP TABLE**: The DROP TABLE statement is used to delete a table from a database.

```sql
DROP TABLE table_name;
```

**JOIN**: The JOIN statement is used to combine rows from two or more tables based on a related column between them.

```sql
SELECT column1, column2, ...
FROM table1
JOIN table2
ON table1.column_name = table2.column_name;
```

**GROUP BY**: The GROUP BY statement is used to group rows based on one or more columns.

```sql
SELECT column1, column2, ...
FROM table_name
GROUP BY column1, column2, ...;
```

**HAVING**: The HAVING statement is used in conjunction with the GROUP BY statement to filter groups based on a condition.

```sql
SELECT column1, column2, ...
FROM table_name
GROUP BY column1, column2, ...
HAVING condition;
```

**ORDER BY**: The ORDER BY statement is used to sort the result-set in ascending or descending order.

```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
```
