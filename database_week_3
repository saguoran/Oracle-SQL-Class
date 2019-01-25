```Oracle SQL

```
##### string concatenation
```Oracle SQL
SELECT Lname || ', ' || Fname AS  Last_name_First_name FROM CUSTOMERS;
SELECT Lname || ', ' || Fname "Last_name_First_name" FROM CUSTOMERS;
```
`GROUP BY COLOMN` return shorter column with non-repeat of the COLUMN values  
```Oracle SQL
SELECT COUNT(*), STATE FROM CUSTOMERS GROUP BY STATE;
-- create a list with count(*) of how many customers in the same state.
```

`TO_DATE('19-JAN-2019','DD-MON-YY')` return date type value with the format of 'DD-MON-YY'
```Oracle SQL
VALUES ('1059831198','BODYBUILD IN 10 MINUTES A DAY',TO_DATE('21-JAN-05','DD-MON-YY'),4,18.75,30.95, NULL, 'FITNESS');
```
`ORDER BY *COLUMN` return same length of rows and certain COLUMN is sorted by ascending order
```Oracle SQL
SELECT * FFROM CUSTOMERS ORDER BY 1;
-- 1 is the first column of the table
```

 ```
 COUNT(COLUMN)
 ```
  `COUNT(ProductName)` return 1 column named `COUNT(ProductName)` with 1 row of number of the ProductName
```
SUM(COLUMN)
```
  `SUM(Price) AS Total`  return 1 column named `Total` with 1 row of total Price of all product price
