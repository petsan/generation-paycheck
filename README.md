# generation-paycheck

Some useful git instructions:

``git clone git@github.com:petsan/generation-paycheck.git``

``git checkout -b your-name``

``git diff``

``git status``

``git add .``

``git commit -m "message text"``

``git push``

Requirements for the Generation Paycheck Calculator

Gather information
1. Ask the user for the name of the person who will receive the paycheck
2. Ask the user for the hourly rate
3. Ask the user for hours
4. Handle invalid input: if a user types in a string that is not a number should tell the user to try again
5. Handle tricky input, i.e.: <0 -1 >168 should provide error message and not crash. 0's should be calculated to 0.

Calculate Regular and O/T pay
1. 0-40 hours is calculated as regular pay
2. over 40 hours is calulated as regular pay times one and a half

Calculate Taxes:
1. Federal Income tax rate: 15%
2. State Income tax rate: 10%
3. FICA: 2%

Print paycheck (For example):
1. Employee: John Doe
2. Hourly rate: $20.27
3. Hours worked: 50.45
4. Regular Pay: $810.80
5. Overtime Pay: $317.73
6. Gross Pay: $1128.53
7. Federal tax: $169.28
8. State Tax: $112.85
9. FICA: $22.57
10. Net Pay: $823.83


BONUS:
Ask how many hours occured during holiday hours and calulate as regular rate times two and over-time as times three

Hints: 
1. use functions for calculations and printing
2. make your code clear and easy to read
 
