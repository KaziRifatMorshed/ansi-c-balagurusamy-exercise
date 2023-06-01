# ANSI C (E. Balagurusamy)
Excersise solutions for the book "ANSI C" by E. Balagurusamy (eight edition). 

# Index
- [Chapter 2](#chapter-2) 

- [Chapter 3](#chapter-3) 

- [Chapter 4](#chapter-4) 

- [Chapter 5](#chapter-5) 

- [Chapter 6](#chapter-6) 

- [Chapter 7](#chapter-7) 

- [Chapter 8](#chapter-8) 

- [Chapter 9](#chapter-9) 

- [Chapter 10](#chapter-10) 

- [Chapter 11](#chapter-11) 

- [Chapter 12](#chapter-12) 

- [Chapter 13](#chapter-13) 

- [Chapter 14](#chapter-14) 

- [Chapter 15](#chapter-15) 

---
## Chapter 2 

1. Write a program to display the equation of a line in the form ax + by = c
for a = 5, b = 8 and c = 18.

2. Write a C program that uses an in-built function to draw a 3D bar.

3. Write a program to output the following multiplication table

4. Given the values of three variables a, b and c, write a program to compute and display the value of x,
where x = a / ( b - c ) 
Execute your program for the following values:
(a) a = 250, b = 85, c = 25
(b) a = 300, b = 70, c = 70
Comment on the output in each case.

5. Write a C program that reads the value of distance travelled by a car and the time taken for the same.
Next, compute the speed at which the car travelled.

6. Write a C program to print the current system date.

7. Given two integers 20 and 10, write a program that uses a function add( ) to add these two numbers
and sub( ) to find the difference of these two numbers and then display the sum and difference in
the following form:
20 + 10 = 30
20 – 10 = 10

8. Modify the above program to provide border lines to the address.

9. Write a program using one print statement to print the pattern of asterisks as shown below:

*
        *  *
        *  *  *
        *  *  *  *
        
10. Write a program that will print the following figure using suitable characters.

11. Area of a triangle is given by the formula
         A = sqrt(s*(s-a)*(S-b)*(s-c))
Where a, b and c are sides of the triangle and 2S = a + b + c. Write a program to compute the area of
the triangle given the values of a, b and c.

12. Write a program to display the following simple arithmetic calculator
       x=                  y=
       sum                 Difference=
       Product=            Division=

13. Distance between two points (x 1, y 1) and (x 2, y 2) is governed by the formula
D2 = (x 2 – x 1)2 + (y 2 – y 1)2
Write a program to compute D given the coordinates of the points.

14. A point on the circumference of a circle whose center is (o, o) is (4,5). Write a program to compute
perimeter and area of the circle. (Hint: use the formula given in the Ex. 2.11)

15. The line joining the points (2,2) and (5,6) which lie on the circumference of a circle is the diameter of
the circle. Write a program to compute the area of the circle.











## Chapter 3 

1. Write a program to determine and print the sum of the following harmonic series for a given value of n:
                        1+ 1/2 +1/3 +....+ 1/n
The value of n should be given interactively through the terminal.

2. The price of one kg of rice is Rs. 16.75 and one kg of sugar is Rs. 15. Write a program to get these values
from the user and display the prices as follows:
      *** LIST OF ITEMS***
      Item          Price
      Rich          Rs 16.75
      Sugar         Rs 15.00

3. Write program to count and print the number of negative and positive numbers in a given set of numbers.
Test your program with a suitable set of numbers. Use scanf to read the numbers. Readingshould be 
terminated when the value 0 is
encountered.

4. Write a program to do the following:
(a) Declare x and y as integer variables and z as a short integer variable.
(b) Assign two 6 digit numbers to x and y
(c) Assign the sum of x and y to z
(d) Output the values of x, y and z
Comment on the output.

5. Write a program to illustrate the use of typedef declaration in a program.

6. Write a program to illustrate the use of symbolicconstants in a real-life application.

7. Write a C program to input an integer and print its table.

8. Write a C program to print the square of a number.

9. Write a C program to input an integer between 0 and 128 and print its ASCII character.

10. Write a C program to input the value of days and convert it into years, weeks and days.

11. Write a C program to input the distance travelled by a car and the fuel consumed. Next,
compute the mileage of the car.

12. Write a C program to input the amount value and break it into the smallest possible 
Indian currency notes.







## Chapter 4 

1. Write a program that reads a floating-point number and then displays the right-most digit of the integral
part of the number.

2. Modify the above program to display the two right most digits of the integral part of the number.

3. Given an integer number, write a program that displays the number as follows:
First line                : all digits
Second line               : all except first digit
Third line                : all except first two digits
.........
Last line                 : The last digit
For example, the number 5678 will be displayed as
              5 6 7 8
              6 7 8
              7 8 
              8
              
4. The straight-line method of computing the yearly depreciation of the value of an item is given by
                  Depreciation = (Purchase Price - Salvage Value) / Years of Service
Write a program to determine the salvage value of an item when the purchase price, years of service,
and the annual depreciation are given.

5. Write a program that will read a real number from the keyboard and print the following output in one
line:
Smallest integer                           The given                   Lergest integer
not less than                               number                     not greater than
the number                                                             the number

6. The total distance travelled by a vehicle in t seconds is given by
distance = ut + ( a t*2 ) / 2
Where u is the initial velocity (metres per second), a is the acceleration (metres per second 2 ). Write a
program to evaluate the distance travelled at regular intervals of time, given the values of u and a.
The program should provide the flexibility to the user to select his own time intervals and repeat the
calculations for different values of u and a .

7. In inventory management, the Economic Order Quantity for a single item is given by
         EOQ = sqrt((2*setup costs) / (demand rate * holding cost per unit time))
  and the optimal Time Between Orders
         TBO = sqrt ((2* setup costs) / (demand rate * holding cost per unit time))
  Write a program to compute EOQ and TBO, given demand rate (items per unit time), setup costs (per
order), and the holding cost (per item per unit time).

8. For a certain electrical circuit with an inductance L and resistance R, the damped natural
frequency is given by
            Frequency = sqrt ((1 / L*C )- (R*R / 4*C*C)
It is desired to study the variation of this frequency with C (capacitance). Write a program to calculate
the frequency for different values of C starting from 0.01 to 0.1 in steps of 0.01.

9. Write a program to read a four digit integer and print the sum of its digits.
Hint: Use / and % operators.

10. Given three values, write a program to read three values from keyboard and print out the largest of
them without using if statement.

11. Write a program to read two integer values m and n and to decide and print whether m is a multiple of n.

12. Write a program to read three values using scanf statement and print the following results:
(a) Sum of the values
(b) Average of the three values
(c) Largest of the three
(d) Smallest of the three

13. The cost of one type of mobile service is Rs. 250 plus Rs. 1.25 for each call made over and above 100
  calls. Write a program to read customer codes and calls made and print the bill for each customer.
  
14. Write a program to print a table of sin and cos functions for the interval from 0 to 180
degrees in increments of 15 a shown here.

15. Write a program to compute the values of square roots and squares of the numbers 0 to 100 in steps
10 and print the output in a tabular form as shown below.

16. Write a program to illustrate the use of cast operator in a real life situation.

17. Write a C program to shift the given data by two bits to the left.

18. Write a C program to compute the value of the expression x=a-b/3+c*2-1.

19. Write a C program to input a date value and determine whether the entered day, month, and
year values are valid.

20. Write a C program to input the sides of a triangle and determine whether the triangle is isoceles or
not.

21. Write a C program that reads two numbers and performs their division. If the division is not
possible, then an error messgage, ‘Division not possible’ is displayed.

22. Input the value of 4 variables a, b, c and d and compute the resultant value of following
expressions:
(a + b) * (c / d)
(a + b) * c / d
a + (b * c) / d









## Chapter 5 

1. Given the string “WORDPROCESSING”, write a program to read the string from the terminal and
display the same in the following formats:
(a) WORD PROCESSING
(b) WORD
PROCESSING
(c) W.P

2. Write a program to read the values of x and y and
print the results of the following expressions in one
line:
(a) (x+y) / (x-y)
(b) (x+y) /2
(c) (x+y)(x–y)

3. Write a program to read the following numbers, round them off to the nearest integers and print out
the results in integer form: 35.7 50.21 – 23.73 – 46.45

4. Write a program that reads 4 floating point values in the range, 0.0 to 20.0, and prints a horizontal bar
chart to represent these values using the character * as the fill character. For the purpose of the chart,
the values may be rounded off to the nearest integer. For example, the value 4.36 should be
represented as follows.
            *      *      *       *
            *      *     *        *         4.36
            *      *     *        *
 Note that the actual values are shown at the end of each bar.

5. Write an interactive program to demonstrate the process of multiplication. The program should ask
the user to enter two two-digit integers and print the product of integers as shown below.
                      45
                  x   37
    ________________________
     7 x 45 is       315
     3 x 45 is       135
     ______________________
     Add them       1665
            _______________

6. Write a program to read three integers from the keyboard using one scanf statement and output
them on one line using:
(a) three printf statements,
(b) only one printf with conversion specifiers, and
(c) only one printf without conversion specifiers.

7. Write a program that prints the value 10.45678 in exponential format with the following specifications:
(a) correct to two decimal places;
(b) correct to four decimal places; and
(c) correct to eight decimal places.

8. Write a program to print the value 345.6789 in fixed-point format with the following specifications:
(a) correct to two decimal places;
(b) correct to five decimal places; and
(c) correct to zero decimal places.

9. Write a program to read the name ANIL KUMAR GUPTA in three parts using the scanf statement and
to display the same in the following format using the printf statement.
(a) ANIL K. GUPTA
(b) A.K. GUPTA
(c) GUPTA A.K.

10. Write a program to read and display the following table of data.
          Name            Code             Price
          Fan             67831            1234.50
          Motor           450              5786.70
The name and code must be left-justified and price must be right justified.

11. Write a C program to print inventory stock report using some sample data. The report should show
item code, quantity and inventory location as formatted output.

12. Write a C program to display the Pascal’s triangle.

13. Write a C program to input a currency value in Dollars and display its equivalent Euro and
INR amounts. You may use current exchange rate for conversion purpose.

14. Write a C program to display the following pattern.
            5 4 3 2 1
              4 3 2 1
                3 2 1
                  2 1
                    1

15. Write a C program to input an investment amount and compute its fixed deposit cumulative return
after 10 years at arate of interest of 8.75%.





## Chapter 6 

1. Write a program to determine whether a given number is ‘odd’ or ‘even’ and print the message
NUMBER IS EVEN or NUMBER IS ODD
(a) without using else option and
(b) with else option.

2. Write a program to find the number of and sum of all integers greater than 100 and less than 200 that
are divisible by 7.

3. A set of two linear equations with two unknowns x1 and x2 is given below:
ax 1 + bx 2 = m
cx 1 + dx 2 = n
The set has a unique solution
	x1 = (m*d - b*n) / (a*d - c*d)
	x2 = (n*a - m*c) / (a*d - c*b)
provided the denominator ad – cb is not equal to zero.
Write a program that will read the values of constants a, b, c, d, m, and n and compute the values of x 1 and x 2. An appropriate message should be printed if ad – cb = 0.

4. Given a list of marks ranging from 0 to 100, write a program to compute and print the number of
students:
(a) who have obtained more than 80 marks,
(b) who have obtained more than 60 marks,
(c) who have obtained more than 40 marks,
(d) who have obtained 40 or less marks,
(e) in the range 81 to 100,
(f) in the range 61 to 80,
(g) in the range 41 to 60, and
(h) in the range 0 to 40.
The program should use a minimum number of if statements.

5. Admission to a professional course is subject to the following conditions:
(a) Marks in Mathematics >= 60
(b) Marks in Physics >= 50
(c) Marks in Chemistry >= 40
(d) Total in all three subjects >= 200
or
Total in Mathematics and Physics >= 150 Given the marks in the three subjects, write a
program to process the applications to list the eligible candidates.

6. Write a program to print a two-dimensional Square Root Table as shown below, to provide the square
root of any number from 0 to 9.9. For example, the value x will give the square root of 3.2 and y the
square root of 3.9.

7. Shown below is a Floyd’s triangle.
1
2 3
4 5 6
7 8 9 10
11 .. .. .. 15
.
.
79 .. .. .. .. .. .. 91
(a) Write a program to print this triangle.
(b) Modify the program to produce the following
form of Floyd’s triangle.
1
0 1
1 0 1
0 1 0 1
1 0 1 0 1

8. A cloth showroom has announced the following seasonal discounts on purchase of items:

Write a program using switch and if statements to compute the net amount to be paid by a customer.



9. Write a program that will read the value of x and evaluate the following function
		    1  for x>0
		y=  0  for x=0
		   -1  for x<0
 using
(a) nested if statements,
(b) else if statements, and
(c) conditional operator ? :

10. Write a program to compute the real roots of a quadratic equation
				ax 2 + bx + c = 0
The roots are given by the equations
		x1 = -b + sqrt ( b*b - 4*a*c) / 2*a
		x2 = -b - sqrt (b*b + 4*a*c) / 2*a
The program should request for the values of the
constants a, b and c and print the values of x 1 and x 2.
 Use the following rules:
(a) No solution, if both a and b are zero
(b) There is only one root, if a = 0 (x = –c/b)
(c) There are no real roots, if b 2 – 4 ac is negative
(d) Otherwise, there are two real roots
Test your program with appropriate data so that all logical paths are working as per your design.
Incorporate appropriate output messages.

11. Write a program to read three integer values from the keyboard and displays the output stating that
they are the sides of right-angled triangle.

12. An electricity board charges the following rates for the use of electricity:
For the first 200 units: 80 P per unit
For the next 100 units: 90 P per unit
Beyond 300 units: Rs 1.00 per unit
All users are charged a minimum of Rs. 100 as meter charge. If the total amount is more than Rs.400, 
then an additional surcharge of 15% of total amount is charged.
Write a program to read the names of users and number of units consumed and print out the
charges with names.



13. Write a program to compute and display the sum of all integers that are divisible by 6 but not divisible
by 4 and lie between 0 and 100. The program should also count and display the number of such
values.



14. Write an interactive program that could read a positive integer number and decide whether the
number is a prime number and display the output accordingly.
Modify the program to count all the prime numbers that lie between 100 and 200.
NOTE : A prime number is a positive integer that is divisible only by 1 or by itself.



15. Write a program to read a double-type value x that represents angle in radians and a character-type
variable T that represents the type of trigonometric function and display the value of
(a) sin(x), if s or S is assigned to T,
(b) cos (x), if c or C is assigned to T, and
(c) tan (x), if t or T is assigned to T
using (i) if......else statement , and (ii) switch statement.

16. Write a C program to input the numeric week day value (starting from Monday as 1) and display the
corresponding name of the week day.



17. Write a C program to input two numbers a and b and display whether
(a) a is greater than b
(b) b is greater than b
(c) or, a and b are equal



18. Write a C program to input the total percentage of marks of a student and display its Division using
below rules:
(a) Greater than or equal to 80 percent - “First Division”
(b) Greater than or equal to 60 percent and less than 80 per cent - “Second Division”
(c) Less than 60 percent - “Third Division"

19. Using Switch case block, input the name of the month from the user and display the corresponding
number of days in that month.



20. Write a C program that inputs a string and counts the number of capital and small alphabets in that
string.

## Chapter 7 

1. Given a number, write a program using while loop to reverse the digits of the number. For example,
the number 12345 should be written as 54321
( Hint: Use modulus operator to extract the last digit and the integer division by 10 to get the n–1
digit number from the n digit number.)
- [sharafat](solutions/sharafat/7/1.c)

2. Write a program to compute the sum of the digits of a given integer number.
- [sharafat](solutions/sharafat/7/2.c)

3. The numbers in the sequence
	1 1 2 3 5 8 13 21 .......
are called Fibonacci numbers. Write a program using a do....while loop to calculate and print the first m
Fibonacci numbers.
( Hint: After the first two numbers in the series, each number is the sum of the two preceding numbers.)
- [sharafat](solutions/sharafat/7/3.c)

4. Write a program to evaluate the following investment equation
				V = P(1+r) n
and print the tables which would give the value of V for various combination of the following values 
of P, r, and n.
P : 1000, 2000, 3000,........, 10,000
r : 0.10, 0.11, 0.12, ......., 0.20
n : 1, 2, 3, ...., 10
( Hint: P is the principal amount and V is the value of money at the end of n years. This equation can
be recursively written as
V = P(1+r)
P = V
That is, the value of money at the end of first year becomes the principal amount for the next year and
so on.)
- [sharafat](solutions/sharafat/7/4.c)

5. Write programs to print the following outputs using for loops.
	(a) 					(b)
		1					* * * * * 
		2 2					  * * * *
		3 3 3					    * * *
		4 4 4 4 					* *
		5 5 5 5 5					  *
- [sharafat](solutions/sharafat/7/5.c)


- [sharafat](solutions/sharafat/7/6.c)

6. Write a program to read the age of 100 persons and count the number of persons in the age group 50 to
60. Use for and continue statements.
- [sharafat](solutions/sharafat/7/7.c)

7. Rewrite the program of case study 7.4 (plotting of two curves) using else...if constructs instead of
continue statements.
- [sharafat](solutions/sharafat/7/8.c)


- [sharafat](solutions/sharafat/7/9.c)

8. Write a program to print a table of values of the function
y = exp (-x)
for x varying from 0.0 to 10.0 in steps of 0.10. The table should appear as follows:
				Table for Y = EXP(–X)
- [sharafat](solutions/sharafat/7/10.c)

9. Write a program using for and if statement to display the capital letter S in a grid of 15 rows and
18 columns as shown below.
* * * * * * * * * * * * * * * * * * * * * * * *
* * - - - - - - - - - - - - - - - - - - - - - - * *
* * * * * * * * * - - - - - - - - - - - - - - * *
* * * *
* * * *
* * * *
- [sharafat](solutions/sharafat/7/11.c)

* * * * * - - - - - - - - - - - - - - - - * * * *
- - - - - - - - - - - - - - - - - - - - - - * * * *
- - - - - - - - - - - - - - - - - - - - - * * * *
- - - - - - - - - - - - - - - - - - - - * * * *
- - - - - - - - - - - - - - - - - - - - * * * *
- - - - - - - - - - - - - - - - - - - - * * * *
* * * * - - - - - - - - — - - - - - - - * * * *
* * * - - - - - - - - - - - - - - - - - * * * *
* * - - - - - - - - - - - - - - - - - - - * * * *
- [sharafat](solutions/sharafat/7/12.c)


- [sharafat](solutions/sharafat/7/13.c)

10. Write a program to compute the value of Euler’s number e, that is used as the base of natural
logarithms. Use the following formula.
		e = 1 + 1/1! + 1 /2! + 1 /3! + . . . . . + 1/n!
Use a suitable loop construct. The loop must terminate when the difference between two
successive values of e is less than 0.00001.
- [sharafat](solutions/sharafat/7/14.c)

11. Write programs to evaluate the following functions to 0.0001% accuracy.
(a) sinx = x – x 3 /3! + x 5 /5! – x 7 /7! + . . . . . .
(b) cosx = 1 – x 2 /2! + x 4 /4! – x 6 /6! + . . . . .
(c) SUM = 1 + (1/2) 2 + (1/3) 3 + (1/4) 4 + … …
- [sharafat](solutions/sharafat/7/15.c)


- [sharafat](solutions/sharafat/7/16.c)

12. The present value (popularly known as book value) of an item is given by the relationship.
			P = pow( (c*(1–d)),n)
	where    c= original cost
		   d= rate of depreciation (per year)
		   n= number of years
		   p= present value after y years.
If P is considered the scrap value at the end of useful life of the item, write a program to compute
the useful life in years given the original cost, depreciation rate, and the scrap value.
The program should request the user to input the data interactively.
- [sharafat](solutions/sharafat/7/17.c)

13. Write a program to print a square of size 5 by using the character N as shown below:
	 (a)								(b)
		n n n n n 							n n n n n
		n n n n n							n       n 
 		n n n n n							n       n 
		n n n n n 							n       n
		n n n n n							n n n n n
- [sharafat](solutions/sharafat/7/18.c)


- [sharafat](solutions/sharafat/7/19.c)

14. Write a program to graph the function
			y = sin (x)
in the interval 0 to 180 degrees in steps of 15 degrees. Use the concepts discussed in the Case Study 4 in Chapter 7.
- [sharafat](solutions/sharafat/7/20.c)



15. Modify the program of Exercise 7.16 to print the character S instead of N at the center of the square as shown below.
				n n n n n 							
				n n n n n						 
 				n n s n n							
				n n n n n 						
				n n n n n

16. Given a set of 10 two-digit integers containing both positive and negative values, write a program using for loop to compute the sum of all positive values and print the sum and the number of values added.
The program should use scanf to read the values and terminate when the sum exceeds 999. Do not use goto statement.



17. Write a C program to display a coloured line.

18. Write a C program to display the following pattern.
			1
		     A B
		    2 3 4
		   C D E F
		  5 6 7 8 9

19. Write a C program to display the following pattern:
			1
 		    1 2 1
		  1 2 3 2 1
		    1	2 1
			1

20. Write a C program to display the following pattern:
		1
		0 1
		1 0 1
		0 1 0 1

## Chapter 8 



## Chapter 9 



## Chapter 10 

1. Write a function exchange to interchange the values of two variables, say x and y. Illustrate the use of this function, in a calling function. Assume that x and y are defined as global variables.

2. Write a function space(x) that can be used to provide a space of x positions between two output numbers. Demonstrate its application.

3. Use recursive function calls to evaluate
	f(x) = x - pow(x,3)/3! + pow(x,5)/5! - pow(x,7)/7! + .....

4. An n_order polynomial can be evaluated as follows:
	P = (.....(((a 0 x+a 1 )x+a 2 )x+a 3 )x+...+a n)
Write a function to evaluate the polynomial, using an array variable. Test it using a main program.



5. The Fibonacci numbers are defined recursively as follows:
				F1 = 1
				F2 = 1
				Fn = Fn-1 + Fn-2 , n>2
Write a function that will generate and print the first n Fibonacci numbers. Test the function for n = 5, 10, and 15.

6. Write a function that will round a floating-point number to an indicated decimal place. For example the number 17.457 would yield the value 17.46 when it is rounded off to two decimal places.



7. Write a function prime that returns 1 if its argument is a prime number and returns zero otherwise.



8. Write a function that will scan a character string passed as an argument and convert all lowercase characters into their uppercase equivalents.



9. Develop a top_down modular program to implement a calculator. The program should request the user to input two numbers and display one of the following as per the desire of the user:
(a) Sum of the numbers
(b) Difference of the numbers
(c) Product of the numbers
(d) Division of the numbers
Provide separate functions for performing various tasks such as reading, calculating and displaying. Calculating module should call second level modules to perform the individual mathematical operations. The main function should have only function calls.



10. Develop a modular interactive program using functions that reads the values of three sides of a triangle and displays either its area or its perimeter as per the request of the user. Given the three sides a, b and c.
		Perimeter = a + b + c
		Area      = sqrt ((s-a)*(s-b)*(s-c))
	where   s 	    - (a+b+c)/2

11. Write a function that can be called to find the largest element of an m by n matrix.



12. Write a function that can be called to compute the product of two matrices of size m by n and n by m. The main function provides the values for m and n and two matrices.



13. Design and code an interactive modular program
that will use functions to a matrix of m by n size,
compute column averages and row averages, and
then print the entire matrix with averages shown in
respective rows and columns.



14. Develop a top-down modular program that will perform the following tasks:
(a) Read two integer arrays with unsorted elements.
(b) Sort them in ascending order
(c) Merge the sorted arrays
(d) Print the sorted list
Use functions for carrying out each of the above tasks. The main function should have only function calls.



15. Develop your own functions for performing following operations on strings:
(a) Copying one string to another
(b) Comparing two strings
(c) Adding a string to the end of another string
Write a driver program to test your functions.



16. Write a program that invokes a function called
find( ) to perform the following tasks:
(a) Receives a character array and a single character.
(b) Returns 1 if the specified character is found in the array, 0 otherwise.



17. Design a function locate ( ) that takes two character arrays s1 and s2 and one integer value m as parameters and inserts the string s2 into s1
immediately after the index m .
Write a program to test the function using a real-life situation. (Hint: s2 may be a missing word in s1 that represents a line of text).



18. Write a function that takes an integer parameter m representing the month number of the year and returns the corresponding name of the month. For instance, if m = 3, the month is March. Test your program.



19. In preparing the calendar for a year we need to know whether that particular year is leap year or not. Design a function leap( ) that receives the year as a parameter and returns an appropriate message.
What modifications are required if we want to use the function in preparing the actual calendar?



20. Write a function that receives a floating point value x and returns it as a value rounded to two nearest decimal places. For example, the value
123.4567 will be rounded to 123.46 (Hint: Seek help of one of the math functions available in math library).

## Chapter 11 



## Chapter 12 



## Chapter 13 



## Chapter 14 



## Chapter 15 



# Contribution

Feel free to contribute. We sincerely appreciate it. Multiple users can contribute to this repository by adding their solutions to the respective folders. The folder structure is as follows:
```
solutions           # Root folder
    name            # Name of the contributor
    ├── 1           # Chapter 1 solutions
    │   ├── 1.c     # Exercise 1.1 solutions
    │   ├── 2.c     # Exercise 1.2 solutions
    │   └── ...     # Other exercises
    ├── 2           # Chapter 2 solutions
    │   ├── 1.c     # Exercise 2.1 solutions
    │   ├── 2.c     # Exercise 2.2 solutions
    │   └── ...     # Other exercises
    └── ...         # Other chapters
``` 
