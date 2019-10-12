# python_data_types
Guide to Data Types in Python

# Data Types

#### Data types are the classification or categorization of data items. Data types represent a kind of value which determines what operations can be performed on that data. Numeric, non-numeric and Boolean (true/false) data are the most used data types.

#### Python has the following standard or built-in data types: Numeric, Boolean, Sequence Type, Dictionary, Mutable and Immutable Objects

## Numeric
#### A numeric value is any representation of data which has a numeric value. 

#### An object of Number data type represents a numeric literal. In computer science, a literal is a notation for representing a fixed value in the source code. For example, in the assignment statement:

```Python
x = 10
```
#### Here 10 is a literal, as the numeric value representing 10 is directly stored in memory. However,
```Python
y = x*2
```
#### Here, even if the expression evaluates to 20, it is not literally included in the source code.


## Python identifies three types of numbers: Integers, Floats, Complex Numbers

## Integer

#### Positive or negative whole numbers (without a fractional part)

#### Integers can be of any length, it is only limited by the memory available. Zero, positive and negative whole numbers without a fractional part and having unlimited precision, e.g. 1234, 0, -456.

#### Integers can be of any length, it is only limited by the memory available.

```Python
a = 1234567890123456789
```
We can call a and receive the following in terminal
```Python
1234567890123456789
```


##### A number having 0o or 0O as prefix represents an octal number.

##### For example: 0O12: equivalent to 10 (ten) in the decimal number system.

##### A number with 0x or 0X as prefix represents hexadecimal number.

##### For example: 0x12: equivalent to 18 (Eighteen) in the decimal number system.

## Float

#### Any real number with a floating point representation in which a fractional component is denoted by a decimal symbol or scientific notation

#### A floating point number is accurate up to 15 decimal places. Integer and floating points are separated by decimal points. 1 is integer, 1.0 is floating point number.

```Python
b = 0.1234567890123456789
```
We can call b and receive the following in terminal
```Python
0.1234567890123456789
```
Notice that the float variable b got truncated.


## Complex Numbers

#### A number with a real and imaginary component represented as x+yj. x and y are floats and j is -1(square root of -1 called an imaginary number)

```Python
>>> c = 1+2j
````
We can call c and receive the following in terminal:
```Python
(1+2j)
```

## Boolean

#### Data with one of two built-in values True or False. Notice that 'T' and 'F' are capital. true and false are not valid booleans and Python will throw an error for them. Boolean values are the two constant objects False and True. In numeric contexts (for example, when used as the argument to an arithmetic operator), they behave like the integers 0 and 1, respectively. 

#### The built-in function bool() can be used to cast any value to a Boolean, if the value can be interpreted as a truth value:

```Python
x = False
print(bool(x)) 
x = True
print(bool(x)) 
x = 5
y = 10
print(bool(x==y)) 
```
Running the above outputs the following in terminal:
```Python
False
True
False
```

## Sequence Type

#### A sequence is an ordered collection of similar or different data types. Python has the following built-in sequence data types:

## String

#### A string value is a collection of one or more characters put in single, double or triple quotes. Multi-line strings can be denoted using triple quotes, ''' or """.


```Python
s = "This is a string"
```
Calling s outputs the following in terminal:
```Python
This is a string
```

## List

#### A list object is an ordered collection of one or more data items, not necessarily of the same type, put in square brackets.


```Python
x = False
print(bool(x)) 
x = True
print(bool(x)) 
x = 5
y = 10
print(bool(x==y)) 
```
Running the above outputs the following in terminal:
```Python
False
True
False
```

## Tuple

#### A Tuple object is an ordered collection of one or more data items, not necessarily of the same type, put in parentheses.


```Python
x = False
print(bool(x)) 
x = True
print(bool(x)) 
x = 5
y = 10
print(bool(x==y)) 
```
Running the above outputs the following in terminal:
```Python
False
True
False
```

## Checking the Type

#### We can use the type() function to know which class a variable or a value belongs to and the isinstance() function to check if an object belongs to a particular class.

```python
a = 5
print(a, "is of type", type(a))

a = 2.0
print(a, "is of type", type(a))

a = 1+2j
print(a, "is complex number?", isinstance(1+2j,complex))
```

#### The above gives us the following output:

```python
5 is of type <class 'int'>
2.0 is of type <class 'float'>
(1+2j) is complex number? True
```

