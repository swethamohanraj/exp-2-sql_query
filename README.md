# Exp_02_SQL-query-to-fetch-the-no_of_works-for-each-department-in-descending-order
## AIM:
### To fetch the given column and arrange the values in descending order using SQL.
## ALGORITHM:
### STEP 1: Create a sample table in SQL using CREATE TABLE syntax
### STEP 2: Insert all the values and Titles respectively using INSERT INTO syntax
### STEP 3: Now check whether all the rows are affected or not by fetching the table
### STEP 4: After checking, now use SELECT for choosing the column name that we meant to sort and use FROM to choose the table
### STEP 5: Then use ORDER BY syntax to sort the rows in ascending or descending order using desc, asc.
### STEP 6: After compiling and running the program, the results will be displayed.
## PROGRAM:
```
create table Employee(
  Sno int,
  Department varchar(50),
  No_of_workers int
);
insert into Employee (Sno,Department,No_of_workers)
values (1,'Development',15);
insert into Employee (Sno,Department,No_of_workers)
values (2,'Frontend Dv',10);
insert into Employee (Sno,Department,No_of_workers)
values (3,'Backend DV',7);
insert into Employee (Sno,Department,No_of_workers)
values (4,'Finance MM',8);
insert into Employee (Sno,Department,No_of_workers)
values (5,'Designer',12);
insert into Employee (Sno,Department,No_of_workers)
values (6,'Marketing',25);
insert into Employee (Sno,Department,No_of_workers)
values (7,'Chief heads',4);
insert into Employee (Sno,Department,No_of_workers)
values (8,'Law persuit',3);

select Department, No_of_workers from Employee
order by Department,No_of_workers desc;
```

## OUTPUT:
![image](https://github.com/gpavithra673/Exp_02_SQL-query-to-fetch-the-no_of_works-for-each-department-in-descending-order/assets/93427264/d1a5e18e-34f7-48c8-878c-9a1392ea8fd0)

## RESULT:
### Thus we have successfully arranged the column values in descending order using the above-given code.
