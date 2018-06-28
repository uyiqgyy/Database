## SQL 

### 1.What is SQL  

> **Structured Query Language**

A **Query Language** is a language in which user requests information from the **database**.

SQL is very widely used query language.

> **database**
we have relational and non-relational database. And the relational model is today the primary data model for commercial data-processing applications.

* structure of relation database

**custormer** relation

customer_name|customer_street|customer_city
--|--|--
Adam|Spring|Pittsfield
Brooks|Senator|Brooklyn
Green|Walnut|Stamford

**branch** relation

branch_name|branch_city|assets
--|--|--
Brighton|Brooklyn|7100000
Downtown|Brooklyn|9000000

**borrower** relation

customer_name|loan_number
--|--
Adams|L-16
Green|L-93

**loan** relation
loan_number|branch_name|amount
--|--|--
L-16|Brighton|900
L-93|Dwntown|4000

### 2. Overview of the SQL Query Language

* Data-definition language - DDL - define/delete/modify relation table
* Data-manipulation language - DML - query/insert/delete/modify rows in relation table
* coulumn type - char, varchar, int, numeric, float...

### 3. 
