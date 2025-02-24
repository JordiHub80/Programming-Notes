# Mathematical Operations in Python

## Basic Operations
This is the way to add, substract, multiply, and divide in Python.

print(5+5) for addition
print(10-5) for substraction
print(5*2) for multiplication
print(10/2) the result will yield a float
print(10//2) the result will yield an integer
print(2**2) for exponents

### Note : Dividing in Python will always result in a float, this is called implicit typecasting

## Flooring
If we want to remove the decimal numbers from an output, we can floor the number using the int() function, which will round the number down to the nearest whole. 

## Rounding
When we want to round in the traditional sense, we need to use the round() function

We can also round to a specific number of decimals by specifying it on the function.

Ex. print (round(3.141627), 2) will create a float rounded to the second decimal.

## Assignment operators
We can use the basic operators next to an equal sign to modify the value of a variable.

score += 1 will add 1 to the variable score
score -= 1 will subtract 1 to the variable score, etc

## f-Strings
We can combine different data type by using an f at the start of a string.

Ex. print(f"Your score is = {score}, your geight is {height})