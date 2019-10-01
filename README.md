# PyCalc

Your objective for this homework is to create a program in python that will act as a calculator. Your calculator should be able to handle two values input by the user, and then either add, subtract, multiply, or divide depending upon user choice.

This is an individual assignment. You can consult with others for specific help, but not for help with your code as a whole. If you have having major issues, come see me.

After you accept this assignment, you can upload your code to the repository created and then commit the changes.

## Considerations

- You should be thinking about code readability and efficiency during this assignment
- See if you can deal with unknown or unexpected inputs
- See if you can make your program deal with non-integers appropriately

#My Code Is:
x = int(input('Enter your first digit here:'))
y = int(input('Enter your second digit here: '))
operation = input('''
Please type in the operation you would like to complete then click enter:
+ for addition
- for subtraction
* for multiplication
/ for division
''')
if operation == '+':
    print(x + y)

if operation == '-':
    print(x - y)
if operation == '*':
    print(x * y)

if operation == '/':
    print(x / y)
