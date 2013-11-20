matrixmath
==========

Some functions for matrix math in JS using TypedArrays

I tried to run some funny numbers through a variety of libraries (numeric.js, sylvester, jsfeat, ndarray for node), none of which had all the functions I needed, and none of the ones with half those functions share a data structure with the library with the other half. So after looking at some benchmark tests for Arrays of Arrays vs TypedArrays in JS, I decided to figure it out on my own. Here are some naive (but toally functional) functions for: transposing a matrix, getting rows, columns, or cells from a matrix, and multiplying matrices using TypedArrays.
