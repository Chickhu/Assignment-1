# Assignment-1
This is my first assignment 

Questions 1 Write a program that asks the user to enter their marks and displays
their grade:
• 90-100: A
• 80-89: B
• 70-79:C
• 60-69: D
Below 60: F
solution 
marks = int(input("Enter the marks: "))

if 90 <= marks <= 100:
    print("A")
elif 80 <= marks < 90:
    print("B")
elif 70 <= marks < 80:
    print("C")
elif 60 <= marks < 70:
    print("D")
else:
    print("Fail")

Questions 2 Write a Python program to check if a given year is a leap year or not.
year=int(input("enter the year : ")>
 if(year%4==0):
 if(year%100==0)
if (year%400==0):
print("this is a leap year")

else:
 print("this is not leap year")
else:
print("this is a leap year")
 else:
print("this is not aleap year")
13 ##enter the year : 2024
14 ##this is a leap year

Questions 3 Take a number and use the += operator to increase its value
a=10
a+=5
print(a)

Questions 4 Explain how Python handles type conversion between different data
types, such as between integers and floats or between strings and lists.
Python handles type conversion in two ways: 

**1. Implicit Type Conversion (Automatic)**
Python automatically converts one data type into another when it makes sense mathematically or logically.  


#### Example:
```python
x = 5      # Integer
y = 2.5    # Float
result = x + y  # x is implicitly converted to float
print(result)   


### **2. Explicit Type Conversion (Type Casting)**
If Python does not automatically convert data types, you can use built-in functions to convert types manually.

#### **Common Type Conversion Functions**
| Function  | Converts To |
|-----------|------------|
| `int(x)`  | Integer    |
| `float(x)` | Float     |
| `str(x)`  | String     |
| `list(x)` | List       |
| `tuple(x)` | Tuple     |
| `set(x)`  | Set       |
| `dict(x)` | Dictionary (from key-value pairs) |

#### **Examples:**

##### **Integer to Float Conversion**
```python
num = 10
converted_num = float(num)
print(converted_num)  # Output: 10.0
```

##### **String to Integer Conversion**
```python
s = "123"
num = int(s)
print(num)  # Output: 123
```
(Note: This works only if the string contains valid numeric characters.)

##### **List to String Conversion**
```python
lst = ['H', 'e', 'l', 'l', 'o']
s = ''.join(lst)  # Joins list elements into a string
print(s)  # Output: Hello
```

##### **String to List Conversion**
```python
s = "Hello"
lst = list(s)
print(lst)  # Output: ['H', 'e', 'l', 'l', 'o']
```

##### **Tuple to List Conversion**
```python
tup = (1, 2, 3)
lst = list(tup)
print(lst)  # Output: [1, 2, 3]
```

##### **List to Tuple Conversion**
```python
lst = [1, 2, 3]
tup = tuple(lst)
print(tup)  # Output: (1, 2, 3)

Questions 5 How do lists and tuples differ in terms of mutability performance? When would you choose one over the other?

1. Mutability: Lists vs. Tuples
Lists are mutable, meaning you can modify, add, or remove elements after creation.
Tuples are immutable, meaning once created, they cannot be changed (no adding, removing, or modifying elements).

2. Performance: Lists vs. Tuples
Tuples are faster than lists because they are immutable and do not require dynamic memory allocation.
Lists are slower because they support operations like appending, inserting, and resizing, which require extra processing.






