# Python Fundamentals I

## Topics covered in today's module

* Introduction to Python
* Data Types
* Data Structures
* I/O
* File I/O

## Main takeaways from doing today's assignment
&minus; Loops headers are much faster to write than java/c++
- Iterate for a range: `for i in range(5):`, `for i in range(1, len(list)):`, at an interval: `for i in range(1, 10, 2):`
- Iterate over list items: `for items in list:`
- Iterate over multiple variables: `for foo, bar in list.items():`

&minus; Sets, tuples, and dictionaries can be used instead of arrays to make searching for elements easier and keep elements paired together
- Sets: Unordered list, capable of set operations (Union, Difference, Intersection, etc)
- Tuples: List of elements with multiple values, keeps connected values together better than lists
- Dictionaries: List of key-value pairs, usually referenced by key string, keeps track of starting index or single connected value

&minus; Use `split()` to create list of strings: `['1', '2', '3', '4', '5']`

## Challenging, interesting, or exciting aspects of today's assignment

&minus; Dictionaries can be sorted by values using:
- `dict(sorted(dictionary.items(), key=lambda item: item[1]))`


Assigning `lambda item: item[1]` to the optional parameter, `key`, tells the `sorted()` function to sort by the second element in each dictionary entry, its value.
Difference between active and passive Neural Language Style Transfer?

## Additional resources used 
https://www.freecodecamp.org/news/sort-dictionary-by-value-in-python/ \
https://stackoverflow.com/questions/613183/how-do-i-sort-a-dictionary-by-value \
https://www.geeksforgeeks.org/python-program-check-string-palindrome-not/ \
https://stackoverflow.com/questions/17331290/how-to-check-for-palindrome-using-python-logic
