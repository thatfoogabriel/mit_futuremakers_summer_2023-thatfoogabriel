# Python Fundamentals II

## Topics covered in today's module

* Object Oriented Programming
* Debugging in Python
* Package Handling

## Main takeaways from doing today's assignment
&minus; You can use conditions and try/excepts for input validation and error handling
- Use `raise` to throw an error with custom message: `raise ZeroDivisionError("Cannot divide by zero!")`
- Use try-except block for custom behavior without messy error output: `except ZeroDivisionError: print("Cannot divide by zero!")`

&minus; Packages and their methods can be renamed for your own readability purposes
- Format: `from "library_name" import "function_name" as "custom_name"`
- Example: `from random import randint as random_integer`

## Challenging, interesting, or exciting aspects of today's assignment
&minus; Python has its own debugger, so no need for IDE with a debugger!
- `breakpoint()` adds stopping point
- `continue` excecutes until next breakpoint
- `next` skips to next line in current function, runs any called functions
- `step` skips to next line, used to peek inside called functions

&minus; It took a while to understand the `self` keyword in classes and how class methods work in general in python
- ***`self` works like `this` in Java, where the object refers to itself***

&minus; Pass `self` as a function argument to modify varibles or list values (No need for public variables like Java)

&minus; When are assertions more useful than using prints or the debugger?
- ***Assertions can tell you why error occurs better than cryptic exception messages. They also help others see what your code assumes or relies on. Doubles as a form of documentation***

## Additional resources used 
[Nested Try-Except Blocks](https://stackoverflow.com/questions/17015230/are-nested-try-except-blocks-in-python-a-good-programming-practice) \
[Alias Imported Function](https://stackoverflow.com/questions/706595/can-you-define-aliases-for-imported-modules-in-python) \
["Self" Keyword in Classes](https://www.geeksforgeeks.org/self-in-python-class/) \
[How to use Superclass Functions](https://realpython.com/python-super/) \
[When Assertions are Useful](https://stackoverflow.com/questions/129120/when-should-i-use-debug-assert)
