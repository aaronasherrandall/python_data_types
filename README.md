# python_data_types
Guide to Data Types in Python

# Data Types

#### Data types are the classification or categorization of data items. Data types represent a kind of value which determines what operations can be performed on that data. Numeric, non-numeric and Boolean (true/false) data are the most used data types.

### Python has the following standard or built-in data types: Numeric, Boolean, Sequence Type, Dictionary, Mutable and Immutable Objects

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


### Python identifies three types of numbers:

### Integer: Positive or negative whole numbers (without a fractional part)
#### Zero, positive and negative whole numbers without a fractional part and having unlimited precision, e.g. 1234, 0, -456.
#### A number having 0o or 0O as prefix represents an octal number.

#### For example: 0O12: equivalent to 10 (ten) in the decimal number system.

#### A number with 0x or 0X as prefix represents hexadecimal number.

#### For example: 0x12: equivalent to 18 (Eighteen) in the decimal number system.

### Float: Any real number with a floating point representation in which a fractional component is denoted by a decimal symbol or scientific notation

### Complex number: A number with a real and imaginary component represented as x+yj. x and y are floats and j is -1(square root of -1 called an imaginary number)

## Boolean

## Sequence Type

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

