Divij Bhandari 
25070123160

Experiment 6 : Study of conditional Statement in python Naman Bothra 25070123078

Aim : Study of conditional Statements in python

Theory: Conditional statements in Python are used to make decisions in a program.
They allow the program to execute different blocks of code based on conditions.
Conditional statements help a program think and decide based on given conditions.

if statement
Executes code only if the condition is true.

Python checks the condition inside if

If the condition is True, the indented code runs

If the condition is False, the code is skipped

2.if–else statement

If the condition is True, the if block runs

If the condition is False, the else block runs

Executes one block if the condition is true, otherwise another.

Only one block (if or else) executes

else has no condition

Algorithm :

Question 1 : Check Whether a Number is Positive, Negative, or Zero

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Check if num is greater than 0.

If true, display "Number is positive".

Else, check if num is less than 0.

If true, display "Number is negative".

Else, display "Number is 0".

Stop

Question 2 : Check Whether a Number is Even or Odd

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Check whether num is divisible by 2.

If num % 2 == 0, display "Number is even".

Otherwise, display "Number is odd".

Stop

Question 3 : Find the Largest of Three Numbers

Start

Prompt the user to enter the first number and store it in variable a.

Prompt the user to enter the second number and store it in variable b.

Prompt the user to enter the third number and store it in variable c.

Compare the three numbers:

If a is greater than or equal to both b and c, display "A is largest" along with a.

Else if b is greater than or equal to both a and c, display "B is largest" along with b.

Else, display "C is largest" along with c.

Stop

Question 4 : Display Grade Based on Marks

Start

Prompt the user to enter the marks.

Read the input and store it in the variable num.

Check the range of marks using conditional statements:

If num is between 90 and 100, display "Grade A".

Else if num is between 75 and 89, display "Grade B".

Else if num is between 60 and 74, display "Grade C".

Else if num is between 40 and 59, display "Grade D".

Else, display "Fail".

Stop

Question 5 : Check Whether a Year is a Leap Year

Start

Prompt the user to enter a year.

Read the input and store it in the variable year.

Check leap year conditions:

If the year is divisible by 400,

OR

If the year is divisible by 4 but not divisible by 100,

then the year is a leap year.

If the above condition is true, display "The year is leap year".

Otherwise, display "The year is not a leap year".

Stop

Question 6 : Increment the Given Date by One Day

Start

Input a date from the user in the format dd/mm/yyyy.

Split the input date into three parts: day (dd), month (mm), and year (yyyy).

Convert dd, mm, and yyyy into integers.

Determine the maximum number of days (max1) in the given month:

If the month is January, March, May, July, August, October, or December, set max1 = 31.

Else if the month is April, June, September, or November, set max1 = 30.

Else if the month is February:

If the year is a leap year, set max1 = 29.

Otherwise, set max1 = 28.

Check whether the month is valid:

If mm < 1 or mm > 12, display "Date is invalid" and stop.

Check whether the day is valid:

If dd < 1 or dd > max1, display "Date is invalid" and stop.

Increment the date:

If dd is less than max1, increment dd by 1.

Else if dd equals max1 and the month is not December:

Set dd = 1

Increment mm by 1

Else if the date is 31/12:

Set dd = 1, mm = 1

Increment yyyy by 1

Display the incremented date.

Stop

Question 7 : Calculate Gross Salary

Start

Prompt the user to enter the basic salary.

Read the input and store it in the variable salary.

Check the salary range:

If salary is less than or equal to 10,000:

Calculate HRA = 20% of salary

Calculate DA = 80% of salary

Gross Salary = salary + HRA + DA

Else if salary is less than or equal to 20,000:

Calculate HRA = 25% of salary

Calculate DA = 90% of salary

Gross Salary = salary + HRA + DA

Else:

Calculate HRA = 30% of salary

Calculate DA = 90% of salary

Gross Salary = salary + HRA + DA

Display the gross salary.

Stop

Question 8 : Calculate Income Tax Based on Slabs

Start

Prompt the user to enter the annual income.

Read the input and store it in the variable inc.

Check the income tax slab and calculate tax accordingly:

If inc is less than or equal to 2,50,000:

Tax = 0

Else if inc is less than or equal to 5,00,000:

Tax = 5% of (inc − 2,50,000)

Else if inc is less than or equal to 10,00,000:

Tax = 5% of 2,50,000

20% of (inc − 5,00,000)

Else:

Tax = 5% of 2,50,000

20% of 5,00,000

30% of (inc − 10,00,000)

Display the calculated tax.

Stop

Queestion 9 : Start

Prompt the user to enter a character.

Read the input and store it in the variable chr.

Create a list vow containing all vowels (both lowercase and uppercase).

Check whether the entered character exists in the vowel list.

If it exists, display “ is a vowel”.

Otherwise, display “It is a consonant”.

Stop

Conclusion :

Hence the program based on if and else loops were run successfully and various activities were performed to build a better understandin of the if and else loops
