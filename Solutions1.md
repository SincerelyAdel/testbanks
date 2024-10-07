
### Elementary Programming

1. **Python Introduction:**
   Python is a high-level, interpreted programming language known for its simplicity and readability. It is beginner-friendly due to its clean syntax and extensive standard library.

2. **Hello, World! Program:**
   ```python
   print("Hello, World!")
   ```

3. **Variables in Python:**
   ```python
   # Example of using variables
   message = "Hello, Python!"
   print(message)
   ```

4. **Basic Arithmetic Operations:**
   ```python
   # Arithmetic operations
   a = 10
   b = 5
   print(a + b)  # Addition
   print(a - b)  # Subtraction
   print(a * b)  # Multiplication
   print(a / b)  # Division
   ```

### Selections

1. **`if` Statement in Python:**
   The `if` statement in Python is used to execute a block of code only if a condition is true.
   
2. **`if-else` Statements:**
   ```python
   # Using if-else statement
   x = 10
   if x > 5:
       print("x is greater than 5")
   else:
       print("x is 5 or less")
   ```

3. **`elif` Usage:**
   ```python
   # Using elif
   num = 0
   if num > 0:
       print("Positive number")
   elif num == 0:
       print("Zero")
   else:
       print("Negative number")
   ```

4. **Logical Operators:**
   ```python
   # Using logical operators
   x = 10
   y = 5
   if x > 5 and y < 10:
       print("Both conditions are true")
   ```

### Mathematical Functions, Strings, and Objects

1. **Mathematical Operations:**
   ```python
   import math
   num = 16
   print(math.sqrt(num))  # Square root
   print(abs(-5))         # Absolute value
   ```

2. **Strings in Python:**
   ```python
   # String manipulation
   my_string = "Python"
   print(my_string.upper())
   ```

3. **Objects in Python:**
   In Python, everything is an object. Objects are instances of classes that can hold both data and methods.

4. **Type Conversion:**
   ```python
   # Type conversion
   num_str = "10"
   num_int = int(num_str)
   ```

### Loops

1. **`for` Loop:**
   ```python
   # Using a for loop
   for i in range(5):
       print(i)
   ```

2. **`while` Loop:**
   ```python
   # Using a while loop
   count = 0
   while count < 5:
       print(count)
       count += 1
   ```

3. **`break` and `continue`:**
   ```python
   # Using break and continue
   for i in range(10):
       if i == 3:
           continue
       if i == 6:
           break
       print(i)
   ```

4. **Iterating Over a List:**
   ```python
   # Iterating over a list
   my_list = [1, 2, 3, 4, 5]
   for item in my_list:
       print(item)
   ```

### Functions

1. **Functions in Python:**
   Functions are reusable blocks of code that perform a specific task. They help in organizing code and making it more readable.

2. **Defining and Calling a Function:**
   ```python
   # Defining and calling a function
   def add(a, b):
       return a + b

   result = add(3, 4)
   print(result)
   ```

3. **Function Arguments:**
   ```python
   # Function arguments
   def greet(name, greeting="Hello"):
       print(f"{greeting}, {name}!")

   greet("Alice")
   ```

4. **Recursive Function:**
   ```python
   # Recursive function
   def factorial(n):
       if n == 0:
           return 1
       return n * factorial(n - 1)

   print(factorial(5))
   ```

### Lists

1. **Lists in Python:**
   ```python
   # Creating and manipulating lists
   my_list = [1, 2, 3, 4]
   my_list.append(5)
   print(my_list)
   ```

2. **List Indexing and Slicing:**
   ```python
   # Indexing and slicing
   my_list = [1, 2, 3, 4, 5]
   print(my_list[0])    # Accessing the first element
   print(my_list[1:3])  # Slicing from index 1 to 2
   ```

3. **List Methods:**
   ```python
   # List methods
   my_list = [1, 2, 3]
   my_list.append(4)
   my_list.insert(1, 5)
   my_list.remove(3)
   my_list.pop()
   print(my_list)
   ```

4. **Iterating Over a List:**
   ```python
   # Iterating over a list
   my_list = [1, 2, 3, 4]
   for item in my_list:
       print(item)
   ```

### More on Strings and Special Methods

1. **String Formatting:**
   ```python
   # String formatting
   name = "Alice"
   age = 30
   print(f"My name is {name} and I am {age} years old.")
   ```

2. **String Methods:**
   ```python
   # String methods
   my_string = "  Hello, World!  "
   print(my_string.upper())
   print(my_string.lower())
   print(my_string.strip())
   print(my_string.split(","))
   ```
