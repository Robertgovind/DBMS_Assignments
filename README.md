# DBMS_Assignments

Lab Practical Question:
1.	(Exercise: retrieve the records from the table) EMPLOYEES (Employee_Id, First_Name, Last_Name, Email, Phone_Number, Hire_Date, Job_Id, Salary, Commission_Pct, Manager_Id, Department_Id)<br>
 a.	create an employee’s table with the following fields: (Emp_id, First_name, Last_name, Phone_No,Hire_date,Job_id,Emp_Salary,Comission_Pct,manager _id,Department_id)<br>
 b.	Insert five records into the table employees<br>
 c.	Display the table Employees<br>
 d.	Find out the employee id, names, salaries of all the employees<br>
 e.	Find the names of the employees who have a salary greater than or equal to 4800<br>
 f.	List out the employees whose last name is ‘AUSTIN’<br>
 g.	Find the names of the employees who works in departments 60,70 and 80<br>
 h.	Display the unique Manager_Id from employees table<br>

2.	(Exercise: update the records in the table) Create Client_master with the following fields (ClientNO, Name, Address, City, State, bal_due)<br>
 a.	create a client master table with attributes<br>
 b.	insert five records into the Client_Master<br>
 c.	Display Client Master Table<br>
 d.	Find the name of Clients whose balance_due >5000<br>
 e.	Change the bal_due of ClientNO “C123” to Rs. 5100<br>
 f.	Change the name of Client_master to Client12<br>
 g.	Display the bal_due heading as “BALANCE” Client master table<br>

3.	Commands of Rollback and Commit : Create Teacher table with the following fields (Name, DeptNo, Date of joining, DeptName, Location, Salary)<br>
 a.	Create Teacher table with the following fields (Id,Name, DeptNo, Date of joining, DeptName, Location, Salary)<br>
 b.	Insert five records<br>
 c.	Give Increment of 25% salary for Mathematics Department.<br>
 d.	Perform Rollback command<br>
 e.	Give Increment of 15% salary for Commerce Department<br>
 f.	Perform commit command<br>

4.	(Exercise on the group by and order by clauses) Create Sales table with the following fields (Sales No, Salesname, Branch, Salesamount, DOB)<br>
 a.	Create a Sales Table with the following fields (Sales_No,Sales_Name,Branch,Sales_Amount,DOB)<br>
 b.	Insert five records<br>
 c.	Calculate total salesamount in each branch<br>
 d.	Calculate average salesamount in each branch<br>
 e.	Display all the salesmen, DOB who are born in the month of December as day in character format i.e. 21-Dec-09<br>
 f.	Display the name and DOB of salesman in alphabetical order of the month.<br>
 
5.	Create an Emp table with the following fields: (EmpNo, EmpName, Job,Basic, DA, HRA,PF, GrossPay, NetPay)<br>
 a.	create an employee table with the following fields: (Emp_No,Emp_ Name, Designation, basic, DA, HRA, PF, Gross pay, Net pay)<br>
 b.	Insert Five Records and calculate GrossPay and NetPay.<br>
 c.	Adding column to table and Updating Attributes DA<br>
 d.	Adding column to table and Updating Attributes HRA<br>
 e.	Adding column to table and Updating Attributes PF<br>
 f.	Adding column to table and Updating Attributes Gross Pay<br>
 g.	Adding column to table and Updating Attributes Net Pay<br>
 g.	Display the employee table<br>
 i.	Display the employees whose Basic is lowest in each department.<br>
 j.	If NetPay is less than Rs. 10,000 add Rs. 1200 as special allowance<br>
 k.	Display the employees whose GrossPay lies between 10,000 & 20,000<br>
 l.	Display all the employees who earn maximum salary.<br>


6.	Employee Database an Enterprise wishes to maintain a database to automate its operations. Enterprise is divided into certain departments and each department consists of employees. The following two tables describes the automation schemas Dept (deptno, dname, loc) Emp (empno, ename, job, mgr, hiredate, sal, comm, deptno)<br>
a.	Create Dept table: Dept (deptno, dname, loc)<br>
b.	Create Dept table: Emp (empno, ename, job, mgr, hiredate, sal, comm, deptno)<br>
c.	Insert data int Dept and Emp tables<br>
d.	Update the employee salary by 15%, whose experience is greater than 30 years<br>
e.	Delete the employees, who completed 30 years of service.<br>
f.	Display the manager who is having maximum number of employees working under him?<br>
g.	Create a view, which contain employee names and their manager<br>


7.	Using Employee Database above perform the following queries<br>
a.	Determine the names of employee, who earn more than their managers.<br>
b.	Determine the names of employees, who take highest salary in their departments.<br>
c.	Determine the employees, who are located at the same place.<br>
d.	Determine the employees, whose total salary is like the minimum Salary of any department.<br>
e.	Determine the department which does not contain any employees.<br>
 
8.	Using the tables “DEPARTMENTS” and “EMPLOYEES” above perform the following queries<br>
a.	Display the employee details, departments that the departments are same in both the emp and dept.<br>
b.	Display the employee name and Department name by implementing a left outer join.<br>
c.	Display the employee name and Department name by implementing a right outer join.<br>
d.	Display the details of those who draw the salary greater than the average salary.<br>

