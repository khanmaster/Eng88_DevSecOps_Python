# Python 
## Python installation 3.7 or above
### Pycharm set up
#### Documentation with README.md to store on Git-hub
##### Dynamically typed language


- Testing the python env `print("hello world")`

- What are variables
    - Variables work as a place holder to store data
    - strings, boolean, integers 
    - "is considered as a String"
    - boolean is true or false
    - numbers are ints


```python
first_name = "Shahrukh" # string

last_name = "Khan" # string
print(first_name)

print(last_name)

Salary = 111 # integer 

print(Salary)

```

```python
print(float_value)
# To find out the type of variable we have method called type()
print(type(float_value))
print(type(Salary))
print(type(first_name))

# Taking user input - we have a method called input()

print("Please enter your name ")
name = input("")
print("Hello")
print(name)

```
### Operators

**Artimetic Operators**
` + - * / `

**Comprison Operators**
`> < == != >= <=  `
`%` Modulus - remainder of the division of left operand by the right

## Arithmetic Operators

| Operand    | Description                          | Example    |
|:---------: |:----------------------------:        |:--------:  |
|    +       | add two operands (variables) together| X + y + 2  |
|    -       | subtract two operands (variables)    | X - y - 2  |
|    *       | multiply two operands (variables)    | X - y - 2  |
|    /       | divide two operands (variables)      | X - y - 2  |
    |    %   | Modulus - remainder of the division of left operand by the right    | X - y - 2  |
|    +       | add two operands (variables) together| X + y + 2  |

## Comparison Operators

| Operand    | Description                          | Example         |
|:---------: |:----------------------------:        |:--------:       |
|    >       | True if left operand is greater than the right| x > y  |
|    <       | True if left operand is less than th
e right| x < y     |
|    ==      | True if both operands are equal            | x == y    |
|    !=      | True if both operands are equal            | x != y    |
|    >=      | True if left operand is greater than or equal to the right| x >= y     |
|    <=      | True if left operand is less than or equal to the right| x <= y     |

```
#  Strings, Concatenation and Casting

single_quotes = 'hello world'

greetings = "Hello World!"
 H E L L O   W O R L  D   !
 0 1 2 3 4 5 6 7 8 9 10  11
# To find out the length of the strings we can use method called len()

print(len(greetings))

# String slicing
print(greetings[0:2])


#
white_spaces = "lot's of spaces at the end                                      "
print("strings with empty spaces")
print(len(white_spaces))
print(len(white_spaces.strip()))
print("strings without spaces")
```
```
Example_text = "here's SOME text with lot's of text"
print(Example_text.count("text")) # count how many times text is written in the string stored in Example test

print(Example_text.lower())#  brings everything lowercase()
print(Example_text.upper()) # changes the string to upper case
print(Example_text.capitalize())

print(Example_text.replace("with", ","))

# Concatenation? combining values, variables, strings together

First_Name = "James"
Last_Name = "Bond"
age = "99"

print(First_Name + " " + Last_Name + " " + (age))
print(f"{First_Name} {Last_Name} is {age}  Old")
```