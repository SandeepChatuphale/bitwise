Employee Creation System
Consider that Employee creation software needs to be developed for computerization of operations of an ABC organization.

1)	Write an Employee class which contains following attributes:

Fields	Data types
id	int
name	String
basicSalary	double
joiningDate	Date

Write showDetails() method which print employee information.
Also write toString() method in Employee class.
id MUST be generated automatically.
Write TestEmployee as a client class.

2)	Refer same Employee Application keep this Employee class inside appropriate package 
Write TestEmployee class and keep that in default package.

3)	Now create a hierarchy: WageEmployee and Manager these are Subclasses of Employee. SalesManager is subclass of Manager.
 

Details of the classes as below:-

Class Name	Attributes
WageEmloyee	hours  ( int )
rate     ( int )


Manager	commision       ( int )

SalesManager	incentives        ( int )
Salary formula :-
WageEmployee : - basicSalary + hours*rate
Manager: - basicSalary + commission;
SalesManager: basicSalary + commission + incentives
NOTE : - USE method overriding. (calculateSalary())

4)	Upgrade the Employee creation system in such a way that  - By using Utility class we should be able print the Employees (Employee, Manager, SalesManager, WageEmployee) details. Using Printable interface.

5)	Upgrade the Employee creation system in such a way that - Use the Same Employee hierarchy, to sort employee on basis of salary and name.

6)	Upgrade the Employee creation system in such a way that now the system should be able to search an employee from a repository of employees based on the employeeId
If user doesn’t find then system should throw a customized exception EmployeeNotFoundException.


7)	 Upgrade the Employee creation system in such a way that now the system should be able to log messages. Make use of File Handling so that all the Log Records are written in to the LOG file named “ECS.log”

8)	Upgrade the Employee creation system in such a way that – create DAO layer and make use of appropriate Collection Framework.

9)	Create table with appropriate columns in mysql DB.
    
10) Update the Employee Creation System in such a way that employees can be persisted inside a Relational Database. Create an table with name tbl_emp where all kinds of employees will be persisted. EMP_TYPE column will identify 3 different kinds of employees like
WE(WageEmployee), M(Manager), SM (SalesManager).

11)	Upgrade the Employee creation system in such a way that – create DAO layer and make use of JDBC and give methods for CRUD Operations.

