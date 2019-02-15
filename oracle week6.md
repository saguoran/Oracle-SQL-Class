    update customer
    set region = '&region'
    where state = 'FL';
    
    SELECT * FROM CUSTOMERS;
    
    UPDATE CUSTOMERS SET Firstname = 'ANNA' where customer# = 1004;
    SAVEPOINT s1;
    commit;
    UPDATE CUSTOMERS SET Firstname = 'ANNA1' where customer# = 1005;
    savepoint s2;
    update customers set firstname = 'ANNA2' where customer# = 1006;
    savepoint s3;
    ROLLBACK TO SAVEPOINT s1;
    ROLLBACK; 
`SAVEPOINT s1;` set up a saveponit S1
`ROLLBACK TO SAVEPOINT s1;` rollback to a savepoint
   `ROLLBACK;`enter code here rollback 

    update customer set middleName = 'NONE' where MiddleName is NULL;

`IS NULL` the value = NULL

select * from customers where state `=` 'NULL';
`= 'NULL'` the value = = 'NULL'
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTg1Nzg0MTY0LDcxODIzNDM1OF19
-->