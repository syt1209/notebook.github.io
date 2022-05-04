### Introduction to Computation and Programming Using Python

[MIT OpenCourseWare](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/) | [Home](./index.md)

**Main Topics**
* [What is computation?](#what-is-computation)
* [Branching and iteration?](#branching-and-iteration)
* [String Manipulation, Guess and Check, Approximations, Bisection](#string-manipulation-guess-and-check-approximations-bisection)
* [Decomposition, Abstractions, Functions](#decomposition-abstractions-functions)
* [Tuples, Lists, Aliasing, Mutability, Cloning](#tuples-lists-aliasing-mutability-cloning)
* [Recursion, Dictionaries](#recursion-dictionaries)
* [Testing, Debugging, Exceptions, Assertions](#testing-debugging-exceptions-assertions)
* [Object Oriented Programming](#object-oriented-programming)
* [Python Classes and Inheritance](#python-classes-and-inheritance)
* [Understanding Program Efficiency](#understanding-program-efficiency)
* [Searching and Sorting algorithms](#searching-and-sorting-algorithms)

#### What is computation

* How to program?
    * represent knowledge with **data structure**
    * **iteration** and **recursion** (control flow)
* How to write "good" code with "good" style?
    * **abstraction** of procedures and data types
    * **organized** and **modular** using object classes and methods
* How to determine program efficiency?
    * **algorithms**
    * **complexity** of algorithms

##### **_What does computer do?_**
* Perform calculations
    * built-in to the language
    * defined by the programmer
* Storage of results

##### **_Types of knowledge_**
* Declarative knowledge -- **statements of fact**
* Imperative knowledge -- **recipe** or **how-to**
    * **What is a RECIPE?**
        1. sequence of simple **steps**
        2. **flow of control** process that specifies when each step is executed
        3. a means of determining **when to stop**
        
******    **_1+2+3 = algorithm!_**   ******

**Basic Machine Architecture**

![basicMachineArchitecture](/assets/basicMachineArchitecture.png)

**Basic primitives**
- Turing: you can compute anything using 6 primitives
- Can abstract method to create new primitives


**Creating recipes**
- a set of **primitive operations** provided by a promgramming language
- **expressions**: complex but legal combinations of primitives
- expressions and computations have values and meanings

**Aspects of languages**
- **_primitive construct_**: numbers, strings, simple operators
- **_syntax_**
- **_static semantics_**: syntactically valid strings have meanings
- **_semantics_**: meaning associated with a syntactically correct string of symbols with no static semantic errors

**ERRORS**
- **_syntatic errors_**
- **_static semantic errors_**
- **_no semantic errors but different meaning than what programmer intended_**

**(Python) Program**
- Sequence of definitions and commands
    - definitions _evaluated_
    - commands _executed_ 

**Objects**
- manipulated by programs
- have a **_type_** that defines things programs can do to them
- **_scalar_**: cannot be subdivided
    - `int` - integers, ex. 7
    - `float` - real numbers, ex. 2.13
    - `bool` - Boolean values, `True` and `False`
    - `NoneType` - special and has one value, `None`
    - `type()` - see the type of an object
    ```python
    >>> type(7)
    int
    ```
    - **Type conversion (CAST)**: convert object of one type to another
        - `float(3)` converts integer `3` to float `3.0`
        - `int(3.9)` truncates float 3.9 to integer `3`
    
    -`print` command shows output from code to a user
    ```python
    In [1]: print(1+1)
    2
    ```
- **_non-scalar_**: have internal structure that can be accessed

**Expressions**
- combine objects and operators
- has a **value**, which has a **type**
- syntax: `<object> <operator> <object>`
    - `i+j`  &rarr; sum
    - `i-j`  &rarr; difference
    - `i*j`  &rarr; product
    - `i/j`  &rarr; division (result is float)
    - `i%j`  &rarr; remainder when `i` is divided by `j`
    - `i**j` &rarr; `i` to the power of `j` 
- `()` tells Python to do these operations first
- operator precedence
    - `**`
    - `*`
    - `/`
    - `+` and `-` executed left to right
- `=` is an *assignment* of a value to a variable name


#### Branching and iteration

- String object type  
    - String  
        - letters, special characters, spaces, digits
        - `hi = "hello"` --enclose in **quotation marks or single quotes**
        - can be **concatenated**
        - `name = "Ann"`
        - `greet = hi + name`
        - operations on a string
        ```python
        silly = hi + " " + name * 3
        ```
- Input/Output: `input()`/`print()`    
        **input() only takes _string_ input**
- Comparison operators on `int, float, string`
    ```python
    i > j
    i >= j
    i < j
    i <= j
    i == j
    i != j
    ```
- Logit operators on `boolean`
    ```python
    not a 
    a and b
    a or b
    ```
  
    `a` | `b` | `a and b` | `a or b`
  ---|---|---|---
  `True`| `True`|`True`|`True`
  `True`|`False`|`False`|`True`
  `False`|`True`|`False`|`True`
  `False`|`False`|`False`|`False`

- Branching and conditionals
    - Control Flow - Branching
    ```python
    if <condition>: # <condition> has a value of True of False
        <expression> # evaluate expression in the block if <condition> is True
        ...
    ---------------------------------------------------------------------------
    if <condition>:
        <expression>
        ...
    else:
        <expression>
        ...
    ---------------------------------------------------------------------------
    if <condition>:
        <expression>
        ...
    elif:
        <expression>
        ...
    else:
        <expression>
        ...
    ```
- Iteration and loops
    - Control Flow - `while` loops
    ```python
    while <condition>:
        <expression>
        ...
    '''
    if <condition> is True, do all the steps inside the while code block;  
    check <condition> again;  
    repeat until <condition> is False.  
    '''
    ```
    - Control Flow - `while` and `for` loops  
    ex. Iterate through numbers in a sequence
    ```python
    # more complicated with while loop
    n = 0
    while n < 5:
        print(n)
        n = n+1
    
    # shortcut with for loop
    for n in range(5):
        print(n)
    ```
    - Control Flow - `for` loops
    ```python
    for <variable> in range(<some_num>):
        <expression>
        ...
    '''
    each time through the loop, <variable> takes a value;  
    first time, <variable> starts at the smallest value;  
    next time, <variable> gets the prev value + 1;  
    etc.  
    '''
    ```
    `range(start, stop, step)`  
    - default values are `start = 0` and `step = 1` and optional  
    - loop until value is `stop - 1`
    
    `break` statement
    - immediately exits whatever loop it is in
    - skips remaining expressions in code block
    - exits only innermost loop!
  
    `for` loops | `while` loops
    --- | ---  
    known number of iterations | unbounded number of iterations
    can end early via `break` | can end early via `break`
    uses a counter | can use a counter but must initialize before loop and increment it inside loop  
    can rewrite a `for` loop using a `while` loop | may not be able to rewrite a `while` loop using a `for` loop  
    
*------coming next------*
#### String Manipulation, Guess and Check, Approximations, Bisection

#### Decomposition, Abstractions, Functions

#### Tuples, Lists, Aliasing, Mutability, Cloning

#### Recursion, Dictionaries

#### Testing, Debugging, Exceptions, Assertions

#### Object Oriented Programming

#### Python Classes and Inheritance

#### Understanding Program Efficiency

#### Searching and Sorting algorithms