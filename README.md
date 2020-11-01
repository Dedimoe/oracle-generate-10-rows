# oracle-generate-10-rows
oracle-generate-10-rows

```
sqlplus> select level n from dual connect by 1=1 and level <= 10;
```

Output:
```
         N
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

```
sqlplus> SELECT LEVEL n FROM DUAL CONNECT BY LEVEL <= 10;
```
Output: 
```
         N
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

```
sqlplus> select rownum n from dual connect by rownum <= 10;
```
Ouput:
```
         N
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

