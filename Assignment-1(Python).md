## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
ANS. Python is simple and easy to code ,which can convert algorithm into machine understanble code so it is called high-level language.
Q2. Why is Python called a dynamically typed language?

Q3. List some pros and cons of Python programming language?
ans.advantages
1.data science library supported,
2.embeddable
3.object oriented supported
4.open source and more readble
cons:
1.speed limitations
2.design restrications

Q4. In what all domains can we use Python?
ans:DS,ML,AI,DE,SCRIPTING,GAME DEVELOPMENT, WEB DEVELOPMENT

Q5. What are variable and how can we declare them?
ANS:any variable should start with alphabet
2.we cannot use special characters 
3.only start with underscore '_'
eg:
_abc=5
a=5
 
Q6. How can we take an input from the user in Python?
ans:name=input()

Q7. What is the default datatype of the value that has been taken as an input using input() function?
ans:string

Q8. What is type casting?
ans:convert datatype to another type 
eg
a=5
b=string(a)
print(type(b))
ans = string

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ans:yes,by split function
syntax:
# taking two inputs at a time
x, y = input("Enter two values: ").split()
print("Number of boys: ", x)
print("Number of girls: ", y)

Q10. What are keywords?
ans:Keywords are predefined, reserved words used in Python programming that have special meanings to the compiler
eg:false ,true,if etc

Q11. Can we use keywords as a variable? Support your answer with reason.
ans:We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.Q12. What is indentation? What's the use of indentaion in Python?

Q13. How can we throw some output in Python?
ans:print function

Q14. What are operators in Python?
ans:Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators

Q15. What is difference between / and // operators?
ans:float division'/',integer division'//'

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ans:"iNeuron"*4

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ans:num = float(input("Enter a number: "))
if num%2 == 0:
  print("the number is even",num)
else:
  print("the number is odd",num)
  
Q18. What are boolean operator?
ans:True , False , not , and , or

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = false

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?
ans:They allow you to make decisions based on the values of variables or the result of comparison

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: if is the first condition check for the condition.

if "if" is False then elif's condition is checked.

else is checked when all the upper condition fails.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ans: age=input("enter the age " )
 if age >=18:
   print("you are eligble")
 else
   print("you are not eligible) 
   
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans:
numbers = [12, 75, 150, 180, 145, 525, 50]

print("Sum number from list : ", sum(numbers))
or
int_list = [12, 75, 150, 180, 145, 525, 50]
list_sum = 0
for num in int_list:
    list_sum = list_sum + num
print("Total sum of elements = ",list_sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ans:numbers = [1,2,3]
    max_number = []
	for i in numbers:
	    if i > max_number
		  max_number = i
		print(max_number)  
		
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
list1 = []
for num in numbers:
  if num > 150:
    if num > 500:
      break
  elif num%5==0:
    list1.append(num) 

print(list1)
