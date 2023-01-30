# **Variables**

Variables are an important part of programming. They are used to store data and information that can be used later in the program. In Python, variables are declared by assigning a value to them. For example, the following code creates three variables and assigns values to them:
````
a = 1 #int
b = 2 #int
c = 3.5 #float
````
The first variable, a, is an integer (int) and is assigned the value of 1. The second variable, b, is also an integer and is assigned the value of 2. The third variable, c, is a float (floating point number) and is assigned the value of 3.5.

Variables can also be used to store strings, which are pieces of text. For example, the following code creates a variable called hi and assigns it the string "hello world!":
````
hi = "hello world!" #string
````
Variables can be overwritten by assigning a new value to them. For example, the following code overwrites the value of the variable a:
````
print(a)
a = 4
print(a)
````
Variables can also be used to get user input. The following code uses the input() function to get the user's name, age, and date of birth:
````
print("Hi, what is your name?")
name = input()
print("Hi, " + name + ". How old are you?")
age = input()
print("Can I also get your date of birth please?")
DOB = input(str())

print("Hi, " + name + " you are " + age + " and was born on " + DOB)
````
Using the variables we have created, we can make a program that takes the user's name, age, and date of birth and prints it back out. The following code does this:
````
name = input("What is your name? ")
age = input("How old are you? ")
DOB = input("What is your date of birth? ")

print("Hi, " + name + " you are " + age + " and was born on " + DOB)
