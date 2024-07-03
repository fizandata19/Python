# Variable in Python
# Variable
a = 1
# a is a variable that stores data inside it.
b = 2
# b is also a variable that stores data inside it.
# DataType
#  int = 12,166,2664
#  float = 23.44,45.55
#  bool = true, false
#  string = "Name"
#  none =
# Logical Operators
a = 2
b = 23
b += 1
print(b)
# Comparison Operators
a = 2
b = 23
print(a < b)
# Write a Python program to add two numbers.
num1 = 2
num2 = 10
c = (num1 + num2)
print(c)
# Write a Python program to find the remainder when a number is divided by z.
a = 10
b = 3
c = a % b
print(c)
# Write a Python for add numbers and input to get a user
a = int(input("Enter a num1: "))
b = int (input("Enter a num2: "))
print("Sum is",(a+b))
u = int(input("Enter a Num1= "))
v = int(input("Enter a Num2= "))
print("Reminder of u divided by v is:",u % v)
# Check the type of variable assigned using input () function
a = input("Enter the value of a: ")
print(type(a))
'''Use comparison operator to find out whether ‘a’ given variable a is greater than
‘b’ or not. Take a = 34 and b = 80'''
a = 34
b = 80
print(a>b)
# Write a python program to find an average of two numbers entered by the user
a = int(input("Enter a num1 = "))
b = int(input("Enter a num2 = "))
c = (a+b)/2
d = round(c)
print(d)
# Write a python program to calculate the square of a number entered by the user.
a = int(input("Enter a num1 = "))
b = a**2
print(b)
# Write a program to print the string through to Index
Text = "Python"
result = Text[2] + Text[-2]
print(result)
#Program for Index
Name = "Fizanlatif"
Name_Short = Name[0:3]
print(Name_Short)
# len function in Python
b = "Fizanlatif"
len(b)
# Missing String in Python
Name = "Fizanlatif"
Name[1:8:2]
# str function in Python
Name = "Fizanlatif"
Name.startswith('Fi')
# Endswith Function in Python
Name = "Fizanlatif"
Name.endswith("fi")
# Title Function in Python
Story = "i am a student"
Story.title()
# Capitalize Function in Python
Name = "fizanlatif"
Name.capitalize()
# UpperCase Function in Python
Name = "Fizanlatif"
Name.upper()
# LowerCase Function in Python
Name = "Fizanlatif"
Name.lower()
# Replace Function in Python
Name = "Fizanlatif"
Name.replace("Fizanlatif","Ali")
# Split Function in Python
Name = "Fizanlatif"
Name.split('Fizan')
# Alnum Function in Python
Name = "Fizanlatif"
Name.isalnum()
# Alpha Function in Python
Name = "Fizanlatif"
Name.isalpha()
c= "Where are you from?\nI am from Pakistan."
print(c)
"""Write a python program to display a user entered name followed by Good
Afternoon using input () function."""
User_Name = input("Enter Your name:")
print(f"{User_Name},Good Morning!")
# Write a program to detect double space in a string.
name = "Fizanl atif"
name.find(" ")
"""Write a program to format the following letter using escape sequence
characters."""
letter = "Dear Harry, \nthis python is nice. \nThanks!"
print(letter.title())
# Sorting function in list
numbers = [1,4,6,7,5,3,2]
numbers.sort()
print(numbers)
# Reverse function in list
numbers = [1,3,5,7,6,4]
numbers.sort()
numbers.reverse()
print(numbers)
# Input the base and height from the user
base = float(input("Enter the length of the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))
# Calculate the area of the triangle
area = 0.5 * base * height
# Display the result
print(f"The area of the triangle is: {area}")
