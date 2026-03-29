## Ex1 : Conditional Statements in Python: Even or Odd Checker

## Aim

To write a Python program to check whether the given number is even or odd using if...else statements.

## Algorithm

1. Get an input from the user.
2. Convert the input to an integer and store it in a variable a.
3. Use the modulo operator % to check if a % 2 == 0.
     If true, print "EVEN".
     Else, print "ODD".
4. End the program.

## Program
 ```
a=int(input("Enter a number:"))
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```
## Output

<img width="583" height="186" alt="Screenshot 2026-03-29 171027" src="https://github.com/user-attachments/assets/2dee489d-4698-4d29-86eb-edf03ae61cad" />

## Result

enter: 8 EVEN


## Ex2 : Datatypes-Boolean Expression Evaluation in Python

## Aim

To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

## Algorithm

1. Set variable a to the result of the expression 0 == True.
2. Set variable b to the result of the expression False == False.
3. Set variable c to the result of the expression True + True.
4. Set variable d to the result of the expression False + 9.
5. Print the value of a with the label "a is".
6. Print the value of b with the label "b is".
7. Print the value of c with the label "c:".
8. Print the value of d with the label "d:".

 ## Program
 ```
 a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output

<img width="580" height="172" alt="Screenshot 2026-03-29 171438" src="https://github.com/user-attachments/assets/e74a4e9c-d2ce-4ce3-bb79-2e0b8e2b5ce8" />

## Result
```
a is False
b is True
c: 2
d: 9
```


## Ex3 : Datatypes-Character Literal in Python

## Aim

To write a Python program that prints the characters 'T' and 'a' using character literals.

## Algorithm
 
Print the character 'T'.
Print the character 'a'.

## Program
```
print('T')
print('a')
```
## Output

<img width="580" height="52" alt="Screenshot 2026-03-29 171811" src="https://github.com/user-attachments/assets/bab7f4b9-8c77-424b-804c-3a98e68a6719" />

## Result

The program successfully displays the characters T and a on separate lines on the screen.


## Ex4 : Datatypes-Complex Number Creation in Python

## Aim

To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## Algorithm

1. Read an integer input from the user and assign it to the variable a (real part).
2. Read another integer input from the user and assign it to the variable b (imaginary      part).
3. Create a complex number x using the complex(a, b) function.
4. Print the complex number x.
5. Print the real part of x using x.real.
6. Print the imaginary part of x using x.imag.

## Program
```
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
```
## Output

<img width="573" height="225" alt="Screenshot 2026-03-29 172143" src="https://github.com/user-attachments/assets/576dc10f-bfb4-4c0d-87c4-d9ec416df22d" />

## Result

Enter the real part: 2 Enter the imaginary part: 3 Complex Number: (2+3j) Real Part: 2.0 Imaginary Part: 3.0


## Ex5 : Datatypes-Read and Print a String in Python

## Aim
 
 To write a Python program to read a string from the user and then print it.

## Algorithm

1. Assign a variable named men_stepped_on_the_moon.
2. Use input() to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program
```
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```
## Output

<img width="362" height="127" alt="Screenshot 2026-03-29 172439" src="https://github.com/user-attachments/assets/8adc4bd2-cdc1-4a62-98d5-7af3675fca46" />

## Result

The program successfully reads a string entered by the user and displays the same string as output.
