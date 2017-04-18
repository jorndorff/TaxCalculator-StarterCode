Tax Calculator
==============

The primary goal of this program is to take the user's income and determine the amount of income tax the user would pay under three different tax plans. 

Assignment
----------
Create a program that will ask the user to enter an income and then calculate the total taxes owed, the percent of gross income paid to taxes, and their net income  for each plan. Name your file `taxCalculator.py`. To figure out how much the income should be taxed, refer to the tables below.


I recommend you take some time and plan your variables and algorithm beforehand - don't just start writing code. As always, comment your code thoroughly, avoid using "magic numbers", and test each case to make sure your program works.


Taxes are Complicated
---------------------
We are ignoring write-offs, credits, deductions, dependents, and all the other stuff that make income tax so complex. We will calculate taxes for a single taxpayer, claiming only him- or herself, taking the standard deduction. The standard deduction is currently $5,800 and a single exemption is $3,700. So each income you can assume will be $9,500 lower than the entered amount, for tax purposes.

If this seems complicated, don't hate me; talk to your congress-people.


The Tax Plans
-------------

###2000 Tax Plan (Final year of Clinton administration)

OVER | NOT OVER | AMOUNT OF TAX
---|---|---
$0 | $2,650 | 0%
$2,650 | $27,850 | 15%
$27,850 | $59,900 |28%
$59,900 | $134,200 | 31%
$134,200 | $289,950 36%
$289,950 | AND OVER | 39.6%


###2008 Tax Plan (Final year of Bush administration)

OVER | NOT OVER | AMOUNT OF TAX
---|---|---
$0|$8,025|10%
$8,025|$32,550|15%
$32,550|$78,850|25%
$78,850|$164,550|28%
$164,550|$357,700|33%
$357,700|AND OVER|35%


###2014 Tax Plan (The most recent data)
**Extra Credit to whomever first get's me the actual 2016 data***

OVER | NOT OVER | AMOUNT OF TAX
---|---|---
$0|$8,700|10%
$8,700|$35,350|15%
$35,350|$85,650|25%
$85,650|$178,650|28%
$178,650|$388,350|33%
$388,350|AND OVER|35%


A Worked Example
----------------
Imagine Jose made $30,000. After subtracting the standard deduction and single exemption, his adjusted income is $20,500. Now according to the year 2000 plan, the first $2650 are taxed at 0%, and dollars 2,651-20,500 are taxed at 15%.

```
Welcome to the tax calculator.
How much gross income did you earn last year?  $30000

Results for the 2000 plan.
Taxes owed: $2677.5
Percent of gross: 9%
Net income: $27322.5

Results for the 2008 plan.
Taxes owed: $2673.75
Percent of gross: 9%
Net income: $27326.25

Results for the 2014 plan.
Taxes owed: $2640.0
Percent of gross: 9%
Net income: $27360.0
```

Enhancements
------------
Feel free to add any functionality to this lab that you'd like. Should your program prompt the user to calculate another income? How does it format output? What if they enter a number that is not valid? Is there anything else the program could output?


Style
-----
The style of your lab is important. You could conceivably solve this problem by using a “brute force” approach without any functions. While this may work, it is not an elegant solution. Efficient program design will be factored into your grade, so be sure to think about layout: are there functions you can design to help break your program into pieces and keep you from having to repeat code? What steps does your algorithm require?

Grading
-------
Category | Points
---------| -------
Used at least one function | 1 points
Effective use of abstraction (subroutines and values) | 3 points
Used git appropriately | 2 points
Calculated correct results for all test cases | 9 points
Wrote clear documentation | 2 points
Handled invalid input gracefully | 1 points
Included some kind of enhancement | 2 points

Remember, a lot of this readme is currently written as an assignment. You should update the readme to be helpful to your users.

Author
------

License
-------

