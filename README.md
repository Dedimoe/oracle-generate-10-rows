# oracle-generate-10-rows
oracle-generate-10-rows

```
sqlplus> select level from dual connect by 1=1 and level <= 10;
```

output:
```
     LEVEL
----------
         1 
         2 
         3 
         4 
         5 
         6 
         7 
         8 
         9 
        10 

 10 rows selected 
```
