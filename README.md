# 30-Days-Python-Learning-Challenge

Welcome to my 30-day Python coding challenge! I'm dedicating the next 30 days to learning Python and building a solid foundation. Every day, I’ll be working on a new topic or concept and uploading my progress here.

---

## 📅 Day 1: Introduction to Python & Strings

### ✅ Topics Covered:
- What is Python?
- Setting up Python (installation & environment)
- Writing your first Python script: `print("Hello, World!")`
- Understanding variables and data types
- Introduction to strings
- String operations: concatenation, repetition, indexing, and slicing
- String methods: `.upper()`, `.lower()`, `.strip()`, `.replace()`, `.find()`, etc.
- Basic input/output with strings

### 📝 Notes:
- Python is a high-level, interpreted programming language known for its simplicity and readability.
- Strings in Python are immutable sequences of characters enclosed in either single `'` or double `"` quotes.
- You can manipulate and analyze strings easily using built-in methods.

- ## 📅 Day 2: Keywords, Identifiers, Variables & Strings Deep Dive

### ✅ Topics Covered:
- Python keywords and their purpose
- Identifiers and naming rules
- Writing single-line and multi-line comments
- Understanding statements in Python
- Variable assignment using `=`
- Multiple assignments in a single line
- Python Data Types:
  - Numeric types: `int`, `float`, `complex`
  - Boolean type: `True`, `False`
  - String type and its properties
- String creation using quotes
- String indexing:
  - Forward indexing (starting from 0)
  - Backward indexing (starting from -1)
- String slicing: extracting substrings
- String updation and deletion (immutability concept)
- String concatenation using `+`

### 📝 Notes:
- **Keywords** are reserved words in Python (like `if`, `else`, `True`, `None`, `import`) that cannot be used as variable names.
- **Identifiers** are names given to variables, functions, classes, etc., and must follow Python’s naming rules (start with a letter or `_`, no special characters or spaces).
- **Comments** make code easier to understand:
  - Single-line: starts with `#`
  - Multi-line: wrapped in triple quotes `'''` or `"""`
- A **statement** is an instruction that the Python interpreter executes. Example: `x = 5`
- Variables are created by assigning values with `=`, and you can assign multiple variables at once like `a, b = 1, 2`.
- **Numeric types** include:
  - `int` for whole numbers (`x = 10`)
  - `float` for decimal numbers (`pi = 3.14`)
  - `complex` for complex numbers (`z = 2 + 3j`)
- **Boolean** values represent truth: `True` or `False`.
- **Strings** are sequences of characters and can be created using single `'`, double `"`, or triple quotes.
- You can access string characters using indexing:
  - Forward indexing: `text[0]` for first character
  - Backward indexing: `text[-1]` for last character
- **Slicing** extracts parts of a string: `text[1:4]` gives characters from index 1 to 3.
- **Strings are immutable**, so they cannot be changed in place. To update, create a new string. Use `del` to delete a string variable.
- **Concatenation** combines strings using the `+` operator: `"Hello " + "World"` results in `"Hello World"`.

 ## 📅 Day 3: Print Statement, String Formatting, End Statement & Separator
### ✅ Topics Covered:

- The print() function in Python

- Using multiple arguments in print()

- Customizing output with the end parameter

- Using the sep parameter to define separators between values

- String formatting using:

- f-strings (formatted string literals)

- .format() method

- % operator

## 📝 Notes:

- The print() function is used to display output to the console.
**Example:-** print("Hello, World!")

- The end parameter in print() lets you control what is printed at the end.
**Example:-** print("Hello", end=" ") will continue on the same line.

- The sep parameter allows you to customize the separator between multiple values.
 **Example:-** print("2025", "04", "19", sep="-") will output 2025-04-19.

### String Formatting Techniques:

- f-strings: name = "Alice"; print(f"Hello, {name}!")

- .format() method: print("Hello, {}!".format(name))

- % formatting: print("Hello, %s!" % name)

- These formatting tools help in producing clean, readable, and dynamic output in Python.
---

# 📘 Python Basics: Arithmetic, Variables, and Comparisons

- **foundational Python concepts** with clear, practical examples. It's perfect for **beginners** who are starting out with Python and want to understand how the language handles numbers, variables, logic, and expressions.

---

## 📌 Topics Covered

### ➕ Arithmetic Operations

Understand how Python performs basic math operations such as:
- **Addition**, **Subtraction**, **Multiplication**
- **Division** (returns a float result)
- **Floor Division** (discards the decimal part)
- **Modulus** (returns the remainder)
- **Exponentiation** (raises a number to a given power)

- These operations form the core of any numerical computation in programming.

---

### 🔢 Number Types

Explore the primary number types in Python:
- **Integers** – whole numbers (e.g., `3`, `42`)
- **Floating-point numbers** – decimals like `3.14`, `9.81`
- **Complex numbers** – include a real and imaginary part (e.g., `1 + 1j`)

Understanding these types is essential for math-heavy or scientific applications.

---

### 🧮 Variables and Assignments

Learn how to:
- Declare and assign values to variables
- Use variables to store results of operations
- Follow naming conventions and avoid overwriting built-in functions

This section helps you understand how data is stored and manipulated in Python.

---

### 📐 Practical Math Examples

Includes simple but useful real-world applications:
- **Area of a Circle** – calculated using radius and π
- **Area of a Rectangle** – using length and width
- **Weight Calculation** – using mass and gravitational force

These examples show how math formulas translate directly into code.

---

### 🔍 Comparison Operators

Explore how to compare values using:
- `==` (Equal), `!=` (Not Equal)
- `>` (Greater Than), `<` (Less Than)
- `>=` (Greater or Equal), `<=` (Less or Equal)

Also includes examples using the `len()` function to compare string lengths.

---

### 🧠 Boolean Logic

Covers the use of:
- `and`, `or`, `not` operators
- Combining multiple conditions
- Evaluating `True` and `False` in logical expressions

Logical operations are crucial for writing conditions, decisions, and loops in programs.

---

### 🧾 Identity and Membership Operators

Introduces:
- `is` and `is not`: Check if two values share the same identity in memory
- `in` and `not in`: Check if a value exists within a string or collection

These operators are useful in data checking, filtering, and string handling.

---
## 📅 Day 4: Working with Lists in Python

## ✅ Topics Covered:
- What is a list in Python?
- Creating and modifying lists
- Indexing and slicing lists
- Nested lists and how to access elements within them
- Looping through lists using `for` and `while` loops
- Checking list membership using `in` and `not in`
- Built-in list methods:
  - `append()`
  - `extend()`
  - `insert()`
  - `remove()`
  - `pop()`
  - `index()`
  - `count()`
  - `sort()` / `sorted()`
  - `reverse()`
- Using `all()` and `any()` for logical checks on list elements

📝 Notes:
- A **list** in Python is an ordered, mutable collection of items, which can be of mixed data types.
- Lists are defined using square brackets `[]`.
- **Indexing** allows access to individual items, while **slicing** helps retrieve subsets of a list.
- Lists can contain other lists (nested lists), and accessing their elements requires multiple indices.
- **Looping** is a powerful way to process each item in a list.
- Use `in` to check if an element exists in a list.
- Python’s built-in list methods make list manipulation easy and efficient.
- `all()` returns `True` if **all** elements in an iterable are true.
- `any()` returns `True` if **any** element in an iterable is true.

---
## 📅 **Day 5: Tuples in Python**  
### ✅ **Topics Covered:**  
- Introduction to Tuples  
- Tuple creation and syntax  
- Indexing and accessing tuple elements  
- Tuple functions: `len()`, `max()`, `min()`, `sum()` (for numeric tuples)  
- `count()` and `index()` methods  
- Checking membership with `in` and `not in`  
- Iterating through a tuple using loops  
- Tuple immutability  
- Deleting a tuple using `del`

📝 **Notes:**  
- **Tuples** are ordered, immutable collections of items. Once created, their elements cannot be changed, making them ideal for storing fixed data.  
- Tuples are defined using **parentheses** `()` and can hold items of **mixed data types**.  
- Since tuples are immutable, operations that would modify their content (like item assignment or deletion) are not allowed.  
- Tuples are **faster than lists** for certain operations and use **less memory**.  
- Useful for **read-only data** or as **keys in dictionaries** (since they're hashable).  

---

# 📅 Day 6: Introduction to Sets in Python
✅ **Topics Covered:**
- What is a Set?
- How to create a Set in Python
- Set properties: unordered, mutable, no duplicates
- Adding elements to a Set: `add()`, `update()`
- Removing elements from a Set: `remove()`, `discard()`, `pop()`
- Set operations:
  - Union (`|`, `union()`)
  - Intersection (`&`, `intersection()`)
  - Difference (`-`, `difference()`)
  - Symmetric Difference (`^`, `symmetric_difference()`)
- Set membership: `in`, `not in`
- Set comparisons: equality and subset/superset checks
- Set comprehensions
- Practical use cases of Sets in Python

📝 **Notes:**
- A Set is an unordered collection of unique elements. It does not allow duplicates and is mutable.
  
- Sets are used to perform mathematical set operations like union, intersection, and difference, which are essential for tasks that involve collections of items with no particular order.
  
- Sets are defined using curly braces `{}` or the `set()` constructor.
  
- Common functions include:
  - `add()`: Adds an element to the set
  - `update()`: Adds multiple elements to the set
  - `remove()`: Removes an element from the set; raises `KeyError` if element does not exist
  - `discard()`: Removes an element from the set without raising an error
  - `pop()`: Removes and returns an arbitrary element
  
- **Set Operations**:
  - **Union**: Combines two sets, eliminating duplicates
    - Example: `set1 | set2` or `set1.union(set2)`
  - **Intersection**: Finds common elements between two sets
    - Example: `set1 & set2` or `set1.intersection(set2)`
  - **Difference**: Returns elements in the first set but not in the second
    - Example: `set1 - set2` or `set1.difference(set2)`
  - **Symmetric Difference**: Returns elements that are in either set, but not both
    - Example: `set1 ^ set2` or `set1.symmetric_difference(set2)`

- **Set Membership**:
  - You can check if an item exists in a set using `in` or `not in`.
  - Example: `"apple" in fruits`

- **Set Comparisons**:
  - You can check for subset, superset, or equality of sets.
  - Example: `set1 <= set2` checks if `set1` is a subset of `set2`

- **Set Comprehensions**:
  - Similar to list comprehensions but for sets. For example, `{x**2 for x in range(10)}` will generate a set of squares.

- **Practical Use Cases**:
  - Removing duplicates from a list: `set(list)`
  - Performing mathematical set operations: Finding common or distinct items between two datasets
 
  ---
  # 📅 Day 7: Working with Dictionaries, Functions, and Loops

## ✅ Topics Covered:

* **Dictionaries:**
    * Introduction to dictionaries: Key-value pairs
    * Creating dictionaries
    * Accessing dictionary items
    * Modifying dictionaries: Adding, updating, and deleting items
    * Dictionary methods: `.keys()`, `.values()`, `.items()`, `.get()`, `.pop()`, `.update()`, etc.
* **Dictionary Functions (as provided in your code):**
    * [Assume you have functions defined in your code that operate on the dictionary. You would list them here with a brief description of what each function does. For example:]
        * `get_value(dictionary, key)`: Retrieves the value associated with a given key in the dictionary.
        * `update_dictionary(dictionary, new_key, new_value)`: Adds or updates a key-value pair in the dictionary.
        * `count_items(dictionary)`: Returns the number of items in the dictionary.
* **Looping Through Dictionaries:**
    * Iterating through keys using a `for` loop
    * Iterating through values using a `for` loop and `.values()`
    * Iterating through key-value pairs using a `for` loop and `.items()`
* **The `range()` Function:**
    * Understanding the `range(stop)` syntax
    * Understanding the `range(start, stop)` syntax
    * Understanding the `range(start, stop, step)` syntax
    * Using `range()` in `for` loops

📝 Notes:

* **Dictionaries:** In Python, dictionaries are unordered collections of key-value pairs. Each key in a dictionary must be unique, and it is used to access its corresponding value. Dictionaries are mutable, meaning you can change their contents after they are created.

* **Dictionary Methods:** Python provides several built-in methods to work with dictionaries, allowing you to efficiently manage and retrieve data.

* **Looping Through Dictionaries:** You can iterate over the elements of a dictionary in various ways depending on whether you need the keys, the values, or both. The `.keys()`, `.values()`, and `.items()` methods provide different views of the dictionary's contents for iteration.

* **The `range()` Function:** The `range()` function is a built-in function that is commonly used to generate a sequence of numbers.
* It is particularly useful when you need to iterate a specific number of times in a `for` loop.

---
# 📅 Day 8: Exploring Operators and Number Systems

## ✅ Topics Covered:

**All Types of Operators:**
* **Arithmetic Operators:** `+` (addition), `-` (subtraction), `*` (multiplication), `/` (division), `//` (floor division), `%` (modulo), `**` (exponentiation).
    * Perform basic mathematical calculations.
* **Assignment Operators:** `=`, `+=`, `-=`, `*=`, `/=`, `//=`, `%=`, `**=`, `&=`, `|=`, `^=`, `>>=`, `<<=`.
    * Assign values to variables and perform operations in place.
* **Comparison Operators:** `==` (equal to), `!=` (not equal to), `>` (greater than), `<` (less than), `>=` (greater than or equal to), `<=` (less than or equal to).
    * Compare values and return a boolean result (`True` or `False`).
* **Logical Operators:** `and`, `or`, `not`.
    * Combine or negate boolean expressions.
* **Identity Operators:** `is`, `is not`.
    * Check if two variables refer to the same object in memory.
* **Membership Operators:** `in`, `not in`.
    * Check if a value exists within a sequence (like lists, strings, tuples).
* **Bitwise Operators:** `&` (AND), `|` (OR), `^` (XOR), `~` (NOT/Complement), `<<` (Left Shift), `>>` (Right Shift).
    * Perform operations on individual bits of integers.

**Number System Conversion:**
* Understanding different number systems: Binary (base-2), Decimal (base-10), Octal (base-8), Hexadecimal (base-16).
* Conversion functions:
    * `bin()`: Converts an integer to its binary representation (prefixed with `0b`).
    * `int(string, base)`: Converts a string representing a number in a given `base` to an integer.
    * `oct()`: Converts an integer to its octal representation (prefixed with `0o`).
    * `hex()`: Converts an integer to its hexadecimal representation (prefixed with `0x`).

**Swap Variable:**
* Different methods to swap the values of two variables:
    * Using a temporary variable.
    * Using simultaneous assignment (Pythonic way): `a, b = b, a`.
    * Using arithmetic operations (less common and can have limitations).
    * Using bitwise XOR operation (efficient for integers).

**Bitwise Operator:**
* Introduction to bitwise operations and their applications.
* Operating directly on the binary representation of integers.

**Complement:**
* The bitwise NOT operator (`~`).
* Inverts each bit of an integer (0 becomes 1, and 1 becomes 0).
* Understanding two's complement representation for signed integers and how the complement works in that context.

**Bitwise AND Operator:**
* The bitwise AND operator (`&`).
* Performs a logical AND on corresponding bits of two operands.
* The resulting bit is 1 only if both corresponding bits are 1; otherwise, it's 0.
* Common uses: Masking specific bits, checking if a particular bit is set.

**Bitwise OR Operator:**
* The bitwise OR operator (`|`).
* Performs a logical OR on corresponding bits of two operands.
* The resulting bit is 1 if at least one of the corresponding bits is 1; it's 0 only if both are 0.
* Common uses: Setting specific bits.

**Bitwise Right and Left Shift Operators:**
* **Left Shift Operator (`<<`):**
    * Shifts the bits of an operand to the left by a specified number of positions.
    * Equivalent to multiplying the number by 2 raised to the power of the shift amount (e.g., `x << n` is roughly equivalent to `x * 2**n`).
    * Zeroes are shifted in from the right.
* **Right Shift Operator (`>>`):**
    * Shifts the bits of an operand to the right by a specified number of positions.
    * Equivalent to integer division of the number by 2 raised to the power of the shift amount (e.g., `x >> n` is roughly equivalent to `x // 2**n`).
    * The behavior of the leftmost bit (sign bit) during a right shift depends on whether the number is signed or unsigned (in Python, it's typically an arithmetic shift for signed integers, preserving the sign).

📝 Notes:

**Operators:** Operators are symbols that perform operations on operands (values or variables). Understanding different types of operators is fundamental for writing any kind of program as they allow you to manipulate data, make comparisons, and control the flow of execution.

**Number Systems:** Computers primarily work with binary numbers. Understanding how to convert between different number systems (binary, decimal, octal, hexadecimal) is crucial for debugging and understanding how data is represented at a low level. Python provides built-in functions to easily perform these conversions.

**Swapping Variables:** Efficiently swapping the values of variables is a common task in programming. Python's simultaneous assignment offers a clean and readable way to achieve this without the need for a temporary variable. The bitwise XOR swap is an interesting technique that works particularly well for integer types, although it might be less intuitive than the temporary variable or simultaneous assignment methods.

**Bitwise Operations:** Bitwise operators are powerful tools for manipulating data at the bit level. They are often used in low-level programming, embedded systems, and situations where performance and memory efficiency are critical. Understanding how these operators work can lead to more optimized and elegant solutions for certain types of problems. The complement, AND, and OR operators form the basis of many bit manipulation techniques. Shift operators are particularly useful for efficient multiplication and division by powers of 2.
  
---
**📅 Day 9: Introduction to Math Modules**

**✅ Topics Covered:**

* **Importing the `math` module:**
    * Using the alias: `import math as m`
    * Importing specific functions: `from math import pow, floor, ceil, ...`
    * Importing all functions: `from math import *` (Note: While convenient, it's generally recommended to import specific functions or use an alias to avoid namespace collisions).
* **Input with Numbers, Integers, and Strings:**
    * Taking numerical input using `input()` and converting it to `int()` or `float()` for mathematical operations.
    * Taking integer input specifically using `int(input())`.
    * Taking string input using `input()`.
* **Slicing Input Functions:**
    * Understanding that `input()` returns a string.
    * Demonstrating how string slicing can be applied directly to the result of the `input()` function to extract specific parts of the user's input.
* **Working with Mathematical Functions (Examples):**
    * Demonstrating the usage of functions like `pow()` (power), `floor()` (floor), and `ceil()` (ceiling) from the `math` module.

**📝 Notes:**

* The `math` module in Python provides access to a wide range of mathematical functions, including trigonometric, logarithmic, exponential, and more.
* When importing modules, using an alias (like `import math as m`) can make your code more concise and readable, especially when you use the module's functions frequently.
* Be mindful of the data type returned by the `input()` function (which is always a string). You'll often need to convert it to an integer or float for mathematical operations.
* String slicing allows you to access specific substrings of the input based on their index. For example, if the user enters "12345", `input()[0:2]` would give you "12".

## 🙌 Acknowledgment

This notebook was created to make **Python learning easy and practical**. The concepts covered here are fundamental and will be valuable for progressing into more advanced Python topics.

---

Feel free to fork the repo, play around with the code, and use it as a learning resource! 🚀


