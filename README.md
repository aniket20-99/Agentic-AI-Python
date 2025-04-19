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

- ## 📅 Day 3: Print Statement, String Formatting, End Statement & Separator
## ✅ Topics Covered:

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

