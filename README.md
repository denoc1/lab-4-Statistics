# lab-4-Statistics

## Background knowledge:
Let ${a_1,a_2,…,a_n}$  be a list of $n$ real numbers.

The average of the list of numbers is $$ave=(a_1+a_2+⋯+a_n)/n$$
		
The variance of the list is given by $var=((a_1-ave)^2+(a_2-ave)^2+⋯+(a_n-ave)^2)/n$

The standard deviation of the list is given by $std=\sqrt(var)$
Hint:  

One way to compute the square root in Java is to use 
      
      Math.sqrt(double value) 

for square root.  For example, Math.sqrt(9.0) is 3.0.  (What happens if you try to do Math.sqrt(9)? )


## Your assignment
- Create a comment header as before, with your name, description, and date.  Also, include credit to any people who assisted you.
- Declare 3 int variables for grades and initialize them to 3 values
- Declare an int variable for the sum of the grades
- Declare a double variable for the average of the grade
- Write a formula to calculate the sum of the 3 grades 
- Write a formula to calculate the average of the 3 grades from the sum using division and type casting.
- Print out the average in a statement.
- Declare a double variable and calculate the variance 
- Declare a double variable to compute the standard deviation. 
- Print out the variance and standard deviation in a sentence

  	For example, your output might look like:


      The three values were 78, 80, and 77.
      Average = 78.33333333333
      Variance = 1.55555555556
      Standard deviation = 1.247219128924647

However, your code should work so that if the three values were changed, the average, variance and standard deviation would all change as well!  (That's how I'll test it.)  Testing your code is an important part of coding.  How should you test your program?  

Here are some sample cases.  Should you test any other scenarios?

    The three values are -14, 23, and 45
    The average is 18.0
    The variance is 592.6666666666666
    The standard deviation is 24.34474618201362


    The three values are -4, 0, and 3
    The average is -0.3333333333333333
    The variance is 8.222222222222221
    The standard deviation is 2.8674417556808756
 
    

