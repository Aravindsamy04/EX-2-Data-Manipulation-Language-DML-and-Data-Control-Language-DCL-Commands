# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
### DATE:

## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![270731124-b32bceb5-9f0f-4c30-b27f-c4375e677f46](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/f364241c-98f5-4cbb-8ad5-bd35e53b3944)


### OUTPUT:
![270731223-3fd9b83b-a6e7-4e47-b0cb-f2815bbbae95](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/ebebb3e5-266f-4298-8a9e-219d29b66f45)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![270718856-15e1ebf0-899f-4589-aee8-0ea4570cefba](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/ad73cb86-2d54-4b15-a025-80e6dbfb5866)


### OUTPUT:
![270731685-ad0c2970-47bc-4591-8f4b-a295a38b092d](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/ca849134-50df-4a6b-bb81-bf937f5811a5)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![270733395-72faf04a-7d00-4070-8b1b-433f67d05a51](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/ce04584d-4856-4711-831c-5f4384de01ac)


### OUTPUT:

![270733298-b697b096-ba16-4329-ac6b-d015128fd061](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/086520f2-5c7e-4837-8499-6085b40d63be)


### Q5)	List the names of Clerks from emp table.

### QUERY:
![270737656-b1f05e5a-a309-424e-b910-cb103f5413e3](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/e95634e8-c36f-43a2-ae0c-121f9649b13e)


### OUTPUT:

![270738265-f8bc5ab3-f99d-400e-aa3f-c1f6c4a06c5d](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/b0acc2bb-3fd1-4b5d-8520-5111010b7a02)

### Q6)	List the names of employee who are not Managers.


### QUERY:

![270738366-01b12f80-95f7-431c-95a7-4470c12c4a72](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/657f0c33-af43-4549-89bc-82e9767fd81b)

### OUTPUT:

![270738422-0cf2a6ad-398f-4d29-bebb-c31a84334347](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/b029d068-fa3f-4089-a0a2-a49215504312)

### Q7)	List the names of employees not eligible for commission.


### QUERY:

![270738943-42336775-5693-4b45-93b4-f60e6b80183c](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/acc730c6-0e69-4748-9615-4c378b44df4f)

### OUTPUT:

![270739010-8f6da561-78ad-4573-9c8b-406de97e5e19](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/498e8898-ebd9-4765-9144-fe7931b253f2)

### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![270739894-63e34f73-6454-4c79-bafd-403fbb23ca66](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/07844485-3324-4ab2-a503-34a149360610)


### OUTPUT:

![270739952-b947469e-7ad5-4b63-966b-652d7d2c8c0f](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/10b8d88a-972c-459c-bc79-3d6910944beb)

### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![270742384-ea09fd51-d67f-4b14-abc7-7093026e69dd](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/55596e26-be7d-4083-a4ca-a269c0f745b8)

### OUTPUT:


### Q10)list the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![270743084-d96047cf-2bbb-4e35-9509-b6948cc69eff](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/4c76bac7-aff4-4148-8b0c-ab30c86040fc)

### OUTPUT:


![270743263-dc101670-2467-428c-bf52-734adc718334](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/5509966d-c259-4915-ab83-b1b8885db7f0)

### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![270743688-b195dae7-d5fb-405b-b0fd-8f3cac28497c](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/14956a81-4042-47da-a537-fc32ce57adae)


### OUTPUT:

![270743781-8366de8d-6502-4a70-a202-8540b84db42c](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/ae608d5e-e010-4d69-b34e-d10e8c7563ab)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![270744159-ab24e141-c401-4a54-92a5-6b83dec1f504](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/175dc73d-dd32-4631-8ca5-cf17d5bd7e54)


### OUTPUT:

![270744231-5b712bd1-29b3-465b-93c0-5076e2aa9128](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/67c4fb9b-5967-41e6-aea5-979fee12dd4f)


### Q13) Find number of rows in the table EMP

### QUERY:

![270744415-c7af2c72-f955-4cfa-925e-e1768eff217b](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/629d1edd-8e99-410f-a241-7dc12d094c27)


### OUTPUT:

![270744469-c5628317-f034-4f88-951c-339f05cd7079](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/723bf6ff-c60c-4ad2-9acc-3ca95f398bca)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![270744958-b50b8a48-eb40-42e5-9fd4-c638757f67ba](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/9ba3e065-8e45-4b16-98c4-8fd83ba8d08e)


### OUTPUT:
![270745021-fa7dd8b3-a982-48f3-b03e-bd7f9152564e](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/70863e49-be60-4b53-a462-195a74183f8a)



### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![270745532-16718b1f-b7d9-4fbf-97df-0b4a4e74466c](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/cb73b924-be12-45f3-bcc8-7abb9b19f1dc)



### OUTPUT:


![270745586-123c7d66-c434-4809-8e89-85fefdf37f24](https://github.com/Aravindsamy04/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/113497037/23a38b3c-e27f-44a0-9afb-cc92f8a9f3e3)
### RESULT :
Thus the Data Manipulation Language (DML) Commands and built in functions in SQL
