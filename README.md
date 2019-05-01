![python](/images/pythonprogramming.png)
# Python Coding Basics
The purpose of this article is to demonstrate the basic coding in Python Programming Language. The code for the same is also provided in "code" folder.
## Outcomes
The reader will get well acquainted with the basic coding syntax of Python Programming Language.
### Example:
```python
print("Basic Coding: Python Programming Language")
```
#### Output:
![python](/images/print.PNG)

## Table of Contents
#### [What is Python?](https://github.com/jimitshah77/Python-Basics/blob/master/README.md#what-is-python-1)
### [Basic Codes](https://github.com/jimitshah77/Python-Basics/blob/master/README.md#basic-codes-1)
#### [1)print()](https://github.com/jimitshah77/Python-Basics/blob/master/README.md#1print-1)
#### [2)Comments](https://github.com/jimitshah77/Python-Basics/blob/master/README.md#2comments-1)
#### [3)Assignment Operator](https://github.com/jimitshah77/Python-Basics/blob/master/README.md#3assignment-operator-1)
#### [4)Input()](https://github.com/jimitshah77/Python-Basics#4input-1)


---

### What is Python?
![python](images/python3.png)

***

## Basic Codes:

### 1)print()
```python
#using double quotes
print("In double quotes")

#using single quotes
print('In single quotes')

#printing a variable
a=10.5
print(a)

#printing with formatting
print("value of a is %f" %a)

print("value of a is {}" .format(a))

#printing multiple variables
x=10
y=20
print('x={0} y={1}'.format(x,y))
print('y={1} x={0}'.format(x,y))


```
#### Output:
![python](/images/print1.PNG)

### 2)Comments
```python
# We use "#" for single line comment

'''
We can write multiline comment using three qoutes(')
The code within the comment must not be executed
print("For example, this line of code will not be executed")
'''

print("And this line of code will be executed")

```
#### Output:
![python](/images/comments.PNG)

### 3)Assignment Operator
```python
# We use "=" for assignment of one value to the variable
a= 10
print("The value of a is "+str(a))
# NOTE: We have to convert int to string for maintaining same type in print statement


# We can also assign multiple variable at a time
b,c=20,30
print("The value of b & c is "+str(b)+"&"+str(c))

#We can also assign value of one variable to another variable
d=a
print("The value of d is "+str(d))
```
#### Output:
![python](/images/assignment_operator.PNG)

### 4)input()
```python
#use input funtion to take the input from the user, pass the information you need as the parameter
x=input("What is your name? ")
print('My name is {0}'.format(x))

#if you want the input to be of string tupe then simply typecast it to integer using the int()
y=int(input("What is your age? "))
print('My age is {0}'.format(y))

```
#### Output:
![python](/images/input.PNG)
