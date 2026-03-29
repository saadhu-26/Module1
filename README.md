Conditional Statements in Python: Even or Odd Checker
🎯 Aim
To write a Python program to check whether the given number is even or odd using if...else statements.

🧠 Algorithm
Get an input from the user.
Convert the input to an integer and store it in a variable a.
Use the modulo operator % to check if a % 2 == 0.
If true, print "EVEN".
Else, print "ODD".
End the program.
🧾 Program
a=int(input("Enter a number:")) if a%2==0: print("EVEN") else: print("ODD")

Output
WhatsApp Image 2025-10-14 at 19 47 55_3eedd69b

Result
enter: 8 EVEN

Ex 1:Datatypes-Boolean Expression Evaluation in Python
🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

🧠 Algorithm
Set variable a to the result of the expression 0 == True.
Set variable b to the result of the expression False == False.
Set variable c to the result of the expression True + True.
Set variable d to the result of the expression False + 9.
Print the value of a with the label "a is".
Print the value of b with the label "b is".
Print the value of c with the label "c:".
Print the value of d with the label "d:".
💻 Program
Add Code here

a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
Output
Screenshot 2025-10-14 194406
Result
a is False
b is True
c: 2
d: 9
Datatypes-Character Literal in Python
🎯 Aim
To write a Python program that prints the characters 'T' and 'a' using character literals.

🧠 Algorithm
Print the character 'T'.
Print the character 'a'.
🧾 Program
print('T')
print('a')
Output
WhatsApp Image 2025-10-14 at 20 00 46_ffaf7bd7

Result
The program successfully displays the characters T and a on separate lines on the screen.

🧮 Datatypes-Complex Number Creation in Python
🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

🧠 Algorithm
Read an integer input from the user and assign it to the variable a (real part).
Read another integer input from the user and assign it to the variable b (imaginary part).
Create a complex number x using the complex(a, b) function.
Print the complex number x.
Print the real part of x using x.real.
Print the imaginary part of x using x.imag.
💻 Program
# Read two integers from the user
x = int(input("Enter the real part: "))
y = int(input("Enter the imaginary part: "))

# Create a complex number using x and y
c = complex(x, y)

# Print the complex number
print("Complex Number:", c)

# Print real and imaginary parts
print("Real Part:", c.real)
print("Imaginary Part:", c.imag)
Output
Screenshot 2025-10-14 200706
Result
Enter the real part: 2 Enter the imaginary part: 3 Complex Number: (2+3j) Real Part: 2.0 Imaginary Part: 3.0

Datatypes-Read and Print a String in Python
🎯 Aim
To write a Python program to read a string from the user and then print it.

🧠 Algorithm
Assign a variable named men_stepped_on_the_moon.
Use input() to read a string from the user and store it in the variable.
Print the value stored in the variable.
🧾 Program
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
Output
image
Result
The program successfully reads a string entered by the user and displays the same string as output.
