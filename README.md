# Milestone-3-Application-Release-2
Overview In this milestone, I designed and developed the second release of their C programming application. 
______________________________________________
Marc Mason

ITT-310

Professor Wright	

October 24, 2021

Milestone 3: Application Release 2
_______________________________________________
**Overview**

In this milestone, students will design and develop the second release of their C programming application. From previous assignments and activities, students should be proficient with the following skills:
1.	Writing C programs that use arrays and pointers
2.	Writing C programs that call user defined functions to make modular code
**Execution**

Execute this assignment according to the following guidelines:
1.	Update the C application to demonstrate the following features: 
a.	Use modular code by using user functions
b.	Use of an array or a pointer
 
2.	All codes should be fully commented with single-line comments for all logic in code statements and multi-line comments for the all functions as well as code modules.
 

3.	Complete test cases using the “Test Case Template,” located in the Course Materials that validates all functionality of the program. Positive, negative, and abuse test cases MUST be included in the assignment.
 
 **GIT LINK**
 https://github.com/masoncota1/Milestone-3-Application-Release-2
 
4.	Update the technical design report with the required design documentation. .
***Calculator application demonstration***

This program will keep executing until the user does not choose the exit option. Here, the do-while loop is used to execute the same logic multiple times.
For the remainder, we defined the function rem() which takes two arguments num1, and num2. The modulus operator doesn’t work on floating-point numbers. So, we should convert the floating-point number into an int data type. Now, We can use the modulus operator, but it returns the result in int. To get the result in the floating-point you can use fmod() function. The fmod() function returns floating-point value.

The calculator application demonstrates the following C program features: basic C code structure, the use of standard input and output, use of variables, and the use of loop and decision. Later iterations of the program with higher functionality will utilize the following: the use of data types, the use preprocessor, the modular code by using user defined functions, the use or array or a pointer, and the use of structure and union. 

The calculator program needs to show options when run 
“Enter Two Numbers” and 
“Enter your choice” (in regard to operands and should provide a list of operators a follows) Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
The calculator application demonstrates the following C program features: basic C code structure, the use of standard input and output, use of variables, and the use of loop and decision. Later iterations of the program with higher functionality will utilize the following: the use of data types, the use preprocessor, the modular code by using user defined functions, the use or array or a pointer, and the use of structure and union. 
In the subsequent iterations of the program, the Acceptance Criterion will help in displaying error messages. For example, 
Acceptance Criterion 1: 
Given that and number are presented for an operation; 
And the logic right; 
Then the respective operation is performed. 
Acceptance Criterion 2: 
Given that entered either the numbers are not numeric;
And or the operant is missing; 
Then error message is displayed and operation does not proceed;
Non-functional requirements will be present in addition to the user requirements. While the user story describes the operations that the application must perform, non-functional requirements list the conditions necessary (that are not always documented) to allow the running the program, such as the presence of input and output hardware that must always be powered to facilitate successful running of the desired programs.  


5.	Complete a screencast, using Loom or a similar free application, that contains a technical walk through of all code and a functional demonstration of the code running on your system
.
6.	Complete a screencast, using Loom or a similar free application, that contains a technical walk through of all code and a functional demonstration of the code running on your system.
***Link to ScreenCast-O-Matic***
https://screencast-o-matic.com/watch/cr63VJVXWIC#

7.	Industry-standard technical writing is required.


***Initial Logic Design***

The program is built using C arithmetic operators. The user is presented with a list of choices. Once the user input their choice that operation is performed. The list of operations presented to the user are addition, subtraction, multiplication and division. The C switch statement and C break and continue will be utilized in this application. The program takes an arithmetic operator (+, -, *, /) and two operands from the user. Then it performs the calculation on the two operands depending on the operator entered by the user. Upon entering an operator, the control of programs jumps to respective case matching the operator. The operation takes place and then the break statement end the switch statement. 
Each arithmetic operator performs their respective operation on user inputs and returns the result.
The following are the list of operations to be used in the program
result = a + b; 
result = a - b; 
result = a * b; 
result = a / b; 
 The calculator program needs to show options when run 
“Enter Two Numbers” and 
“Enter your choice” (in regard to operands and should provide a list of operators a follows) Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)

The calculator application demonstrates the following C program features: basic C code structure, the use of standard input and output, use of variables, and the use of loop and decision. Later iterations of the program with higher functionality will utilize the following: the use of data types, the use preprocessor, the modular code by using user defined functions, the use or array or a pointer, and the use of structure and union. 
In the subsequent iterations of the program, the Acceptance Criterion will help in displaying error messages. For example, 
Acceptance Criterion 1: 
Given that and number are presented for an operation; 
And the logic right; 
Then the respective operation is performed. 
Acceptance Criterion 2: 
Given that entered either the numbers are not numeric;
And or the operant is missing; 
Then error message is displayed and operation does not proceed;
Non-functional requirements will be present in addition to the user requirements. While the user story describes the operations that the application must perform, non-functional requirements list the conditions necessary (that are not always documented) to allow the running the program, such as the presence of input and output hardware that must always be powered to facilitate successful running of the desired programs.  


