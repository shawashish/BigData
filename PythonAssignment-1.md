## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
A1. Python is called as a general purpose and high level programming language because it is easy to write and understand. Moreover it can be used to create a variety of different programs and isn't specialized for any specific problems.

Q2. Why is Python called a dynamically typed language?
A2. It is called as dynamically typed language because type of variable declaration is not needed in python. It identifies the type of variable by itself during runtime.

Q3. List some pros and cons of Python programming language?
A3. Pros:
    Python is high level programming language easy to read and write.
    Python is dynamically capable of identifying all sorts of variables.
    Python is general purpose and can be used for a variety of problem statements.
    Cons:
    Python is weak in mobile computing and browsers.
    It is more suitable in the server side not in the client side.

Q4. In what all domains can we use Python?
A4. Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game           Development to Web Development.

Q5. What are variable and how can we declare them?
A5. Variables are symbolic reference to an object. We can simply type the name of the variable and assign the value to it. There is no need to explicitly define the data type of the variable.

Q6. How can we take an input from the user in Python?
A6. Using input function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
A7. string.

Q8. What is type casting?
A8. Type casting is converting a set of data type to one of our required data types.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A9. Yes we can, by using split function.

Q10. What are keywords?
A10. Keywords in python are inbuilt standard functions of python which are meant to perform specfic task.

Q11. Can we use keywords as a variable? Support your answer with reason.
A11. Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and variable name.

Q12. What is indentation? What's the use of indentation in Python?
A12. Indentation refers to the spaces at the beginning of a code line. In python indentation is used to segregate specific block of code.

Q13. How can we throw some output in Python?
A13. Using print function.

Q14. What are operators in Python?
A14. In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands. A sequence of operands and operators, like a + b - 5 , is called an expression. Python supports many operators for combining data objects into expressions.

Q15. What is difference between / and // operators?
A15. / stands for normal division whereas // stands for float division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
A16. 
str_value = 'iNeuron'
str_value = str_value*4
print(str_value)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A17.
# Input Function
int_value = int(input('Enter a number'))
if int_value % 2 == 0:
    print('Even Number')
else:
    print('Odd Number')

Q18. What are boolean operator?
A18. Boolean operators are Python's built-in data types. It's used to represent the truth value of an expression. 

Q19. What will the output of the following?
```
1 or 0
A19. Output: 1

0 and 0
Output: 0

True and False and True
Output: False

1 or 0 or 0
Output:  1
```

Q20. What are conditional statements in Python?
A20. A conditional statement is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Q21. What is use of 'if', 'elif' and 'else' keywords?
A21. The if / elif / else structure is a common way to control the flow of a program, allowing you to execute specific blocks of code depending on the value of some data.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A22.
age = int(input('Enter the age'))
if age >=18:
    print('I can vote')
else:
    print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A23.
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for item in numbers:
    if item %2==0:
        sum = sum + item

print("The sum of all even numbers is: ", sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A24.
# Greatest number as output

x = list(map(int, input("Enter multiple values: ").split()))
print(max(x))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A25.
numbers = [12, 75, 150, 180, 145, 525, 50]
my_list = []
for item in numbers:
    if item %5 ==0 and item <= 150:
        my_list.append(item)
    elif item > 500:
        break
    elif item > 150:
        continue

print(my_list)