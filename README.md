**Python Programming Fundamentals**

This syllabus covers essential concepts and skills in Python programming.

**Section 1: Computer Programming and Python Fundamentals (18%)**

**Objectives covered by the block (7 exam items)**

**PCEP-30-02 1.1 – Understand fundamental terms and definitions**
- Interpreting and the interpreter, compilation and the compiler
- Lexis, syntax, and semantics

**PCEP-30-02 1.2 – Understand Python’s logic and structure**
- Keywords
- Instructions
- Indentation
- Comments

**PCEP-30-02 1.3 – Introduce literals and variables into code and use different numeral systems**
- Boolean, integers, floating-point numbers
- Scientific notation
- Strings
- Binary, octal, decimal, and hexadecimal numeral systems
- Variables
- Naming conventions
- Implementing PEP-8 recommendations

**PCEP-30-02 1.4 – Choose operators and data types adequate to the problem**
- Numeric operators: ** * / % // + –
- String operators: * +
- Assignment and shortcut operators
- Unary and binary operators
- Priorities and binding
- Bitwise operators: ~ & ^ | << >>
- Boolean operators: not, and, or
- Boolean expressions
- Relational operators ( == != > >= < <= )
- The accuracy of floating-point numbers
- Type casting

**PCEP-30-02 1.5 – Perform Input/Output console operations**
- The print() and input() functions
- The sep= and end= keyword parameters
- The int() and float() functions

**Section 2: Control Flow – Conditional Blocks and Loops (29%)**

**Objectives covered by the block (8 exam items)**

**PCEP-30-02 2.1 – Make decisions and branch the flow with the if instruction**
- Conditional statements: if, if-else, if-elif, if-elif-else
- Multiple conditional statements
- Nesting conditional statements

**PCEP-30-02 2.2 – Perform different types of iterations**
- The pass instruction
- Building loops with while, for, range(), and in
- Iterating through sequences
- Expanding loops with while-else and for-else
- Nesting loops and conditional statements
- Controlling loop execution with break and continue

**Section 3: Data Collections – Tuples, Dictionaries, Lists, and Strings (25%)**

**Objectives covered by the block (7 exam items)**

**PCEP-30-02 3.1 – Collect and process data using lists**
- Constructing vectors
- Indexing and slicing
- The len() function
- List methods: append(), insert(), index(), etc.
- Functions: len(), sorted()
- The del instruction
- Iterating through lists with the for loop
- Initializing loops

**PCEP-30-02 3.2 – Collect and process data using tuples**
- Tuples: indexing, slicing, building, immutability
- Tuples vs. lists: similarities and differences
- Lists inside tuples and tuples inside lists

**PCEP-30-02 3.3 Collect and process data using dictionaries**
- Dictionaries: building, indexing, adding and removing keys
- Iterating through dictionaries and their keys and values
- Checking the existence of keys
- Methods: keys(), items(), and values()

**PCEP-30-02 3.4 Operate with strings**
- Constructing strings
- Indexing, slicing, immutability
- Escaping using the \ character
- Quotes and apostrophes inside strings
- Multi-line strings
- Basic string functions and methods

**Section 4: Functions and Exceptions (28%)**

**Objectives covered by the block (8 exam items)**

**PCEP-30-02 4.1 – Decompose the code using functions**
- Defining and invoking user-defined functions and generators
- The return keyword, returning results
- The None keyword
- Recursion

**PCEP-30-02 4.2 – Organize interaction between the function and its environment**
- Parameters vs. arguments
- Positional, keyword, and mixed argument passing

**PCEP-30-02 4.3 – Python Built-In Exceptions Hierarchy**
- BaseException
- Exception
- SystemExit
- KeyboardInterrupt
- Abstract exceptions
- ArithmeticError
- LookupError
- IndexError
- KeyError
- TypeError
- ValueError

**PCEP-30-02 4.4 – Basics of Python Exception Handling**
- Try-except / the try-except Exception
- Ordering the except branches
- Propagating exceptions through function boundaries
- Delegating responsibility for handling exceptions

**Section 5: Modules and Packages (12%)**

**Objectives covered by the block (6 exam items)**

**PCAP-31-03 5.1 – Import and use modules and packages**
- Import variants: import, from import, import as, import *
- Advanced qualifying for nested modules
- The dir() function
- The sys.path variable

**PCAP-31-03 5.2 – Perform evaluations using the math module**
- Functions: ceil(), floor(), trunc(), factorial(), hypot(), sqrt()

**PCAP-31-03 5.3 – Generate random values using the random module**
- Functions: random(), seed(), choice(), sample()

**PCAP-31-03 5.4 – Discover host platform properties using the platform module**
- Functions: platform(), machine(), processor(), system(), version(), python_implementation(), python_version_tuple()

**PCAP-31-03 5.5 – Create and use user-defined modules and packages**
- Idea and rationale
- The __pycache__ directory
- The __name__ variable
- Public and private variables
- The __init__.py file
- Searching for/through modules/packages
- Nested packages vs. directory trees

**Section 6: Exceptions (14%)**

**Objectives covered by the block (5 exam items)**

**PCAP-31-03 6.1 – Handle errors using Python-defined exceptions**
- Except, except:-except, except:-else:, except (e1, e2)
- The hierarchy of exceptions

**PCAP-31-03 6.2 – Extend the Python exceptions hierarchy with self-defined exceptions**
- Self-defined exceptions
- Defining and using self-defined exceptions

**Section 7: Strings (18%)**

**Objectives covered by the block (8 exam items)**

**PCAP-31-03 7.1 – Understand machine representation of characters**
- Encoding standards: ASCII, UNICODE, UTF-8, code points, escape sequences

**PCAP-31-03 7.2 – Operate on strings**
- Functions: ord(), chr()
- Indexing, slicing, immutability
- Iterating through strings, concatenating, multiplying, comparing (against strings and numbers)
- Operators: in, not in

**PCAP-31-03 7.3 – Employ built-in string methods**
- Methods: .isxxx(), .join(), .split(), .sort(), sorted(), .index(),

**Section 8: Object-Oriented Programming (34%)**

**Objectives covered by the block (12 exam items)**

**PCAP-31-03 8.1 – Understand the Object-Oriented approach**
- Ideas and notions: class, object, property, method, encapsulation, inheritance, superclass, subclass, identifying class components

**PCAP-31-03 8.2 – Employ class and object properties**
- Instance vs. class variables: declarations and initializations
- The __dict__ property (objects vs. classes)
- Private components (instances vs. classes)
- Name mangling

**PCAP-31-03 8.3 – Equip a class with methods**
- Declaring and using methods
- The self parameter

**PCAP-31-03 8.4 – Discover the class structure**
- Introspection and the hasattr() function (objects vs classes)
- Properties: __name__, __module__, __bases__

**PCAP-31-03 8.5 – Build a class hierarchy using inheritance**
- Single and multiple inheritance
- The isinstance() function
- Overriding
- Operators: not is, is
- Polymorphism
- Overriding the __str__() method
- Diamonds

**PCAP-31-03 8.6 – Construct and initialize objects**
- Declaring and invoking constructors

**Section 9: Miscellaneous (22%)**
**Objectives covered by the block (9 exam items)**

**PCAP-31-03 9.1 – Build complex lists using list comprehension**
- List comprehensions: the if operator, nested comprehensions

**PCAP-31-03 9.2 – Embed lambda functions into the code**
- Lambdas: defining and using lambdas
- Self-defined functions taking lambdas as arguments
- Functions: map(), filter()

**PCAP-31-03 9.3 – Define and use closures**
- Closures: meaning and rationale
- Defining and using closures

**PCAP-31-03 9.4 – Understand basic Input/Output terminology**
- I/O modes
- Predefined streams
- Handles vs. streams
- Text vs. binary modes

**PCAP-31-03 9.5 – Perform Input/Output operations**
- The open() function
- The errno variable and its values
- Functions: close(), .read(), .write(), .readline(), readlines()
- Using bytearray as input/output buffer

This syllabus provides a comprehensive understanding of Python's logic, syntax, essential programming constructs, control flow, data collections, functions, exceptions, modules, packages, object-oriented programming, and miscellaneous advanced topics, preparing learners for proficiency in Python programming.
