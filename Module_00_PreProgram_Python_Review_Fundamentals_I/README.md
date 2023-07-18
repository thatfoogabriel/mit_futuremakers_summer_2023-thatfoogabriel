# Python Fundamentals I

## Topics covered in today's module

* Introduction to Python
* Data Types
* Data Structures
* I/O
* File I/O

## Main takeaways from doing today's assignment
&minus; Loops headers are much faster to write than java/c++
- &bull; Iterate for a range: `for i in range(5):`, `for i in range(1, len(list)):`, at an interval: `for i in range(1, 10, 2):`
- &bull; Iterate over list items: `for items in list:`
- &bull; Iterate over multiple variables: `for foo, bar in list.items():`
<br></br>

&minus; Sets, tuples, and dictionaries can be used instead of arrays to make searching for elements easier and keep elements paired together
- &bull; Sets: Unordered list, capable of set operations (Union, Difference, Intersection, etc)
- &bull; Tuples: List of elements with multiple values, keeps connected values together better than lists
- &bull; Dictionaries: List of key-value pairs, usually referenced by key string, keeps track of starting index or single connected value
<br></br>

&minus; Use `split()` to create list of strings: `['1', '2', '3', '4', '5']`

## Challenging, interesting, or exciting aspects of today's assignment

&minus; Dictionaries can be sorted by values using:
- `dict(sorted(dictionary.items(), key=lambda item: item[1]))`


Assigning `lambda item: item[1]` to the optional parameter, `key`, tells the `sorted()` function to sort by the second element in each dictionary entry, its value.
Difference between active and passive Neural Language Style Transfer?

## Additional resources used 
[Sort Dictionary by Value](https://www.freecodecamp.org/news/sort-dictionary-by-value-in-python/) \
[Sort Dictionary by Value](https://stackoverflow.com/questions/613183/how-do-i-sort-a-dictionary-by-value) \
[Check String for Palindrome](https://www.geeksforgeeks.org/python-program-check-string-palindrome-not/) \
[Check String for Palindrome](https://stackoverflow.com/questions/17331290/how-to-check-for-palindrome-using-python-logic)
