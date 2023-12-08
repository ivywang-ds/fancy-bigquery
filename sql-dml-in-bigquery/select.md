---
description: Definition of SELECT and FROM with code examples
---

# SELECT

SELECT is the most common operation in SQL, called "the query". SELECT retrieves data from one or more tables, or expressions.

The FROM clause indicates the table or tables that you want to retrieve data.

1. **Retrieve all records from  a table**

`SELECT * FROM`` `_`table_name`_`;`

2. **Retrieve records from specific columns in a table.**

`SELECT`` `_`column1`_`,`` `_`column2, ...`_`FROM`` `_`table_name`_`;`

3. **Retrieve only distinctive records (In this way, we can skip the duplicated records)**

`SELECT DISTINCT`_`column1`_`,`` `_`column2, ...`_`FROM`` `_`table_name`_`;`

4. **Retrieve records except specific columns**

`SELECT`` `_`*`_` ``EXCEPT (`_`column_name`_`) FROM`` `_`table_name`_`;`

