Download Link: https://assignmentchef.com/product/solved-cis247-week-6
<br>
4.8/5 - (6 votes)

1.    We are going to create an abstract Employee class and two pure virtual functions – calculatePay() and displayEmployee(). The abstract Employee class will prevent a programmer from creating an object based on Employee, however, a pointer can still be created. Objects based on Salaried and Hourly will be allowed. The pure virtual function calculatePay() in Employee will force the child classes to implement calculatePay(). The other pure virtual function displayEmployee() in Employee will force the child classes to implement displayEmployee().2.    We are going to implement Polymorphism and dynamic binding in this iLab.

STEP 1: Understand the UML DiagramNotice in the updated UML diagram that the Employee class is designated as abstract by having the class name Employee italicized. Also, the calculatePay method is italicized, which means that it is a pure virtual function and needs to be implemented in the derived classes. In addition, make displayEmployee() method a pure virtual function as well.

STEP 2: Create the ProjectCreate a new project and name it CIS247C_WK6_Lab

STEP 3: Modify the Employee Class1.    Define calculatePay() as a pure virtual function.

2.    Define displayEmployee() as a pure virtual function.

3.    When class Employee contains two pure virtual functions, it becomes an abstract class.

STEP 4: Create Generalized Input MethodsReuse method getInput() from the previous iLab to prompt the user to enter Employee information.

STEP 5: Modify the Main MethodCreate two employee pointers with:

The first employee pointer refers to a salaried employee and the second employee pointer refers to a hourly employee.

Prompt the user to enter information for these two pointers and display the calculated result.

For salaried employee, the following information needs to be displayed:

Partial Sample Output:

For hourly employee, the following information needs to be displayed:

Partial Sample Output:

STEP 6: Compile and TestWhen done, compile and run your code. Then, debug any errors until your code is error-free. Check your output to ensure that you have the desired output, modify your code as necessary, and rebuild. Below is a complete sample program output for your reference.

STEP 7: Submit Deliverables·         Capture the Console output window and paste it into a Word document