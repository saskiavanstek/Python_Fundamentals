---
title: Variables and Types
level: beginner
---

Python is completely object oriented, and not "statically typed". 
You do not need to declare variables before using them, or declare their type. Every variable in Python is an object.

# Numbers

Python supports two types of numbers:

- Integers(whole numbers)
- floating point(decimals)

>[!NOTE]
>It also supports complex numbers, which will not be explained in this tutorial
>

To define an integer, use the following syntax:
````python
myint = 7
print(myint)
````
Als je een drijvendekommagetal wilt definiëren, kunt u een van de volgende notaties gebruiken:

````python
myfloat = 7.0
print(myfloat)
myfloat = float(7)
print(myfloat)
````
To define a floating point number, you may use one of the following notations:

````python
myfloat = 7.0
print(myfloat)
myfloat = float(7)
print(myfloat)
````
# Strings

Strings are defined either with a single quoate or double quotes.

````python
mystring = 'hello'
print(mystring)
mystring = "hello"
print(mystring)
````
The difference between the two is that using double quotes makes it easy to include apostrophes. 
If we would use single qoutes it would terminate the string.

````python
mystring = "Don't worry about apostrophes"
print(mystring)
````
Simple operators can be executed on numbers and strings:

````python
one = 1
two = 2
three = one + two
print(three)

hello = "hello"
world = "world"
helloworld = hello + " " + world
print(helloworld)
````
Assignments can be done on more than one variable on the same line like this:

````python
a, b = 3, 4
print(a, b)
````
Mixing operators between numbers and strings is not supported:

````python
# This will not work!
one = 1
two = 2
hello = "hello"

print(one + two + hello)
````

