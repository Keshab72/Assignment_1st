# Assignment_1st
SQL Assignment 1


## Problem Statement:-
ABC Fashion is a leading retailer with a vast customer base and a team of dedicated sales representatives. They have a Sales Order Processing System that helps manage customer
orders and interactions.

## Dataset:-
Find the dataset  information and the script for the table creation and record insertion " Tables & Records for SQL Assignment 1 " file

## Tools:-
-  MS SQL server

## Tasks to be Performed:-

1. Insert a new record in your Orders table.
2. Add Primary key constraint for SalesmanId column in Salesman table. Add default constraint for City column in Salesman table. Add Foreign key constraint for SalesmanId column in Customer table. Add not null constraint in Customer_name column for the Customer table.
3. Fetch the data where the Customer’s name is ending with ‘N’ also get the purchase amount value greater than 500.
4. Using SET operators, retrieve the first result with unique SalesmanId values from two tables, and the other result containing SalesmanId with duplicates from two tables.
5. Display the below columns which has the matching data. Orderdate, Salesman Name, Customer Name, Commission, and City which has the range of Purchase Amount between 500 to 1500.
6. Using right join fetch all the results from Salesman and Orders table.

## Data Analysis:-


- Inserting  a new record in your Orders table
```sql
  INSERT INTO Orders (OrderId, CustomerId, SalesmanId, Orderdate, Amount) 
  Values (5002,2345,101,'2023-07-01',555)
  select* from Orders
```

 Add Foreign key constraint for SalesmanId column in Customer table
 ```sql
alter table Salesman
add constraint fk_SalesmanId
foreign key (SalesmanId) references Salesman(SalesmanId)
```

Remaining Queries is available in "SQL Assignment 1" file 

## THANK YOU 

