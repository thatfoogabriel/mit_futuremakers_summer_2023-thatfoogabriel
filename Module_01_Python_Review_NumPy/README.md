# NumPy

## Topics covered in today's module

* Introduction to NumPy
* Arrays/Matrices
* Matrix operations

## Main takeaways from doing today's assignment
<img src="https://ml-cheatsheet.readthedocs.io/en/latest/_images/dynamic_resizing_neural_network_4_obs.png" width=40% height=40%> \
&minus; AI/ML is coded in Python because of its efficiency of performing operations on arrays and matrices, which I know are crucial for building neural networks
- <ins>Manipulation:</ins> Merge: `concatenate(a, b, axis)`, Duplicate across axes: `repeat(a, num_repeats, axis)`, Reshape Dimensionally:
- - `transpose(row, col, page)`
- <ins>Indexing:</ins> Subset: `array[2]` `array[1, 2]`, Slice: `array[0:2]` `array[0:2, 1]` `array[:1]`, Filter: `array[array < 2]`
- <ins>Matrix Math:</ins> Multiplication: `np.array([a * b])`, Dot Product: `dot(a, b)`, Inverse: `linalg.inv(a)`, Determinant: `linalg.det(a)`, Rank:
- - `linalg.matrix_rank(a)`
- <ins>Useful:</ins> Reverse Array: `array[::-1]`, Compare by Element: `arrayA < array` `arrayA == arrayB`, Min/Max Value: `array.min()` `array.max()`

## Challenging, interesting, or exciting aspects of today's assignment
&minus; It was challenging to visualize dimensions changing or multiplying like in questions 3 and 4 \
<img src="https://i.stack.imgur.com/bJjF0.png" width=30% height=30%> <img src="https://i.stack.imgur.com/2KGGE.png" width=60% height=60%> 
- Matrices are stored as arrays with markers where new dimensions start 

<img src="https://i.stack.imgur.com/SeWB2.png" width=30% height=30%> <img src="https://i.stack.imgur.com/pnjys.png" width=60% height=60%> 
- `array.transpose(1, 0, 2)` swaps the first two dimensions, swapping the corresponding markers in memory

## Additional resources used 
[NumPy Documentation](https://numpy.org/doc/stable/index.html) \
[NumPy for Linear Algebra](https://www.geeksforgeeks.org/numpy-linear-algebra/) \
[Axis Permutation with Transpose Function ](https://stackoverflow.com/questions/32034237/how-does-numpys-transpose-method-permute-the-axes-of-an-array)
