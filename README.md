# EX-3-SubQueries-Views-and-Joins

## AIM :

To create a database and execute DDL queries using SQL.

## Query :

SubQueries, Views 


## SQL QUERY :

 CREATE VIEW student AS SELECT id,name,age FROM stud WHERE id < 2;

 ## OUTPUT :

![Screenshot 2023-09-25 234916](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/0ba4cc4e-daca-4b10-975e-c7a9edd1c79b)


###  INSERT VIEW :

## SQL QUERY :

INSERT INTO stud(id,name,marks,age) VALUES(6,'dhanraj',85,23);

 INSERT INTO stud(id,name,marks,age) VALUES(8,'raj',75,22);

 ## OUTPUT :

 ![Screenshot 2023-09-25 233032](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/06fce5c0-8205-440e-a356-2591e3797bcf)

## DELETE VIEW :


## SQL QUERY :

 DELETE FROM stud WHERE id=6;

## OUTPUT :

![Screenshot 2023-09-25 233201](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/cbc5796e-31b3-4141-90a8-8df73007d96f)



## TABLE :

![Screenshot 2023-09-25 233744](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/84d3d295-4f6b-4a0d-9a28-9aab2db07abd)


![Screenshot 2023-09-25 233804](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/599cede0-7819-4056-bf06-4ef032c2801c)


## JOIN:

Join table 1 and table2 : emp & emp1

## SQL QUERY :

 SELECT emp.id,emp.name,emp1.id FROM emp INNER JOIN emp1 ON emp.id=emp1.id;

## OUTPUT :

![Screenshot 2023-09-25 233914](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/2a683aa2-4129-4e39-9e02-f1d331151496)


### INNER JOIN :

## SQL QUERY :

 SELECT emp.id,emp.name,emp1.id FROM emp INNER JOIN emp1 ON emp.id=emp1.id;

 ## OUTPUT :

 ![Screenshot 2023-09-25 234022](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/580717de-51ed-46a0-83e3-7695d25e49df)


## LEFT JOIN :

## SQL QUERY :

 SELECT emp.id,emp.name,emp1.id FROM emp LEFT JOIN emp1 ON emp.id=emp1.id;

 ## OUTPUT :

 ![Screenshot 2023-09-25 234243](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/c5dbdab6-de31-45e9-8137-20cc90b84608)


## RIGHT JOIN :

## SQL QUERY :

SELECT emp.id,emp.name,emp1.id FROM emp RIGHT JOIN emp1 ON emp.id=emp1.id;

## OUTPUT :

![Screenshot 2023-09-25 234417](https://github.com/Abrinnisha6/EX-3-SubQueries-Views-and-Joins/assets/118889454/e6a313cf-b607-4858-b7cb-14de43ac1518)

## FULL JOIN :


## SQL QUERY :

## OUTPUT :

## NATURAL JOIN :

## SQL QUERY :

## OUTPUT :









 
