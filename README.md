# DBMS_Assignments

Lab Practical Question:
1.	(Exercise: retrieve the records from the table) EMPLOYEES (Employee_Id, First_Name, Last_Name, Email, Phone_Number, Hire_Date, Job_Id, Salary, Commission_Pct, Manager_Id, Department_Id)
 1.	create an employee’s table with the following fields: (Emp_id, First_name, Last_name, Phone_No,Hire_date,Job_id,Emp_Salary,Comission_Pct,manager _id,Department_id)
 2.	Insert five records into the table employees
 3.	Display the table Employees
 4.	Find out the employee id, names, salaries of all the employees
 5.	Find the names of the employees who have a salary greater than or equal to 4800
 6.	List out the employees whose last name is ‘AUSTIN’
 7.	Find the names of the employees who works in departments 60,70 and 80
 8.	Display the unique Manager_Id from employees table

2.	(Exercise: update the records in the table) Create Client_master with the following fields (ClientNO, Name, Address, City, State, bal_due)
 1.	create a client master table with attributes
 2.	insert five records into the Client_Master
 3.	Display Client Master Table
 4.	Find the name of Clients whose balance_due >5000
 5.	Change the bal_due of ClientNO “C123” to Rs. 5100
 6.	Change the name of Client_master to Client12
 7.	Display the bal_due heading as “BALANCE” Client master table

3.	Commands of Rollback and Commit : Create Teacher table with the following fields (Name, DeptNo, Date of joining, DeptName, Location, Salary)
 1.	Create Teacher table with the following fields (Id,Name, DeptNo, Date of joining, DeptName, Location, Salary)
 2.	Insert five records
 3.	Give Increment of 25% salary for Mathematics Department.
 4.	Perform Rollback command
 5.	Give Increment of 15% salary for Commerce Department
 6.	Perform commit command

4.	(Exercise on the group by and order by clauses) Create Sales table with the following fields (Sales No, Salesname, Branch, Salesamount, DOB)
 1.	Create a Sales Table with the following fields (Sales_No,Sales_Name,Branch,Sales_Amount,DOB)
 2.	Insert five records
 3.	Calculate total salesamount in each branch
 4.	Calculate average salesamount in each branch
 5.	Display all the salesmen, DOB who are born in the month of December as day in character format i.e. 21-Dec-09
 6.	Display the name and DOB of salesman in alphabetical order of the month.
 
5.	Create an Emp table with the following fields: (EmpNo, EmpName, Job,Basic, DA, HRA,PF, GrossPay, NetPay)
 1.	create an employee table with the following fields: (Emp_No,Emp_ Name, Designation, basic, DA, HRA, PF, Gross pay, Net pay)
 2.	Insert Five Records and calculate GrossPay and NetPay.
 3.	Adding column to table and Updating Attributes DA
 4.	Adding column to table and Updating Attributes HRA
 5.	Adding column to table and Updating Attributes PF
 6.	Adding column to table and Updating Attributes Gross Pay
 7.	Adding column to table and Updating Attributes Net Pay
 8.	Display the employee table
 9.	Display the employees whose Basic is lowest in each department.
 10.	If NetPay is less than Rs. 10,000 add Rs. 1200 as special allowance
 11.	Display the employees whose GrossPay lies between 10,000 & 20,000
 12.	Display all the employees who earn maximum salary.


6.	Employee Database an Enterprise wishes to maintain a database to automate its operations. Enterprise is divided into certain departments and each department consists of employees. The following two tables describes the automation schemas Dept (deptno, dname, loc) Emp (empno, ename, job, mgr, hiredate, sal, comm, deptno)
1.	Create Dept table: Dept (deptno, dname, loc)
2.	Create Dept table: Emp (empno, ename, job, mgr, hiredate, sal, comm, deptno)
3.	Insert data int Dept and Emp tables
4.	Update the employee salary by 15%, whose experience is greater than 30 years
5.	Delete the employees, who completed 30 years of service.
6.	Display the manager who is having maximum number of employees working under him?
7.	Create a view, which contain employee names and their manager


7.	Using Employee Database above perform the following queries
a.	Determine the names of employee, who earn more than their managers.
b.	Determine the names of employees, who take highest salary in their departments.
c.	Determine the employees, who are located at the same place.
d.	Determine the employees, whose total salary is like the minimum Salary of any department.
e.	Determine the department which does not contain any employees.
 
8.	Using the tables “DEPARTMENTS” and “EMPLOYEES” above perform the following queries
a.	Display the employee details, departments that the departments are same in both the emp and dept.
b.	Display the employee name and Department name by implementing a left outer join.
c.	Display the employee name and Department name by implementing a right outer join.
d.	Display the details of those who draw the salary greater than the average salary.

