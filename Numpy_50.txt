
#### 1. Import the numpy package under the name `np` (★☆☆)
`hint: import … as`
#### 2. Print the numpy version and the configuration (★☆☆)
`hint: np.__version__, np.show_config)`
#### 3. Create a null vector of size 10 (★☆☆)
`hint: np.zeros`
#### 4. How to find the memory size of any array (★☆☆)
`hint: size, itemsize`
#### 5. How to get the documentation of the numpy add function from the command line? (★☆☆)
`hint: np.info`
#### 6. Create a null vector of size 10 but the fifth value which is 1 (★☆☆)
`hint: array[4]`
#### 7. Create a vector with values ranging from 10 to 49 (★☆☆)
`hint: arange`
#### 8. Reverse a vector (first element becomes last) (★☆☆)
`hint: array[::-1]`
#### 9. Create a 3x3 matrix with values ranging from 0 to 8 (★☆☆)
`hint: reshape`
#### 10. Find indices of non-zero elements from [1,2,0,0,4,0] (★☆☆)
`hint: np.nonzero`
#### 11. Create a 3x3 identity matrix (★☆☆)
`hint: np.eye`
#### 12. Create a 3x3x3 array with random values (★☆☆)
`hint: np.random.random`
#### 13. Create a 10x10 array with random values and find the minimum and maximum values (★☆☆)
`hint: min, max`
#### 14. Create a random vector of size 30 and find the mean value (★☆☆)
`hint: mean`
#### 15. Create a 2d array with 1 on the border and 0 inside (★☆☆)
`hint: array[1:-1, 1:-1]`
#### 16. How to add a border (filled with 0's) around an existing array? (★☆☆)
`hint: np.pad`
#### 17. What is the result of the following expression? (★☆☆)
```python
0 * np.nan
np.nan == np.nan
np.inf > np.nan
np.nan - np.nan
np.nan in set([np.nan])
0.3 == 3 * 0.1
```
`hint: NaN = not a number, inf = infinity`
#### 18. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal (★☆☆)
`hint: np.diag`
#### 19. Create a 8x8 matrix and fill it with a checkerboard pattern (★☆☆)
`hint: array[::2]`
#### 20. Consider a (6,7,8) shape array, what is the index (x,y,z) of the 100th element? (★☆☆)
`hint: np.unravel_index`
#### 21. Create a checkerboard 8x8 matrix using the tile function (★☆☆)
`hint: np.tile`
#### 22. Normalize a 5x5 random matrix (★☆☆)
`hint: (x -mean)/std`
#### 23. Create a custom dtype that describes a color as four unsigned bytes (RGBA) (★☆☆)
`hint: np.dtype`
#### 24. Multiply a 5x3 matrix by a 3x2 matrix (real matrix product) (★☆☆)
`hint:`
#### 25. Given a 1D array, negate all elements which are between 3 and 8, in place. (★☆☆)
`hint: >, <`
#### 26. What is the output of the following script? (★☆☆)
```python
# Author: Jake VanderPlas

print(sum(range(5),-1))
from numpy import *
print(sum(range(5),-1))
```
`hint: np.sum`
#### 27. Consider an integer vector Z, which of these expressions are legal? (★☆☆)
```python
Z**Z
2 << Z >> 2
Z <- Z
1j*Z
Z/1/1
Z<Z>Z
```
`No hints provided...`
#### 28. What are the result of the following expressions? (★☆☆)
```python
np.array(0) / np.array(0)
np.array(0) // np.array(0)
np.array([np.nan]).astype(int).astype(float)
```
`No hints provided...`
#### 29. How to round away from zero a float array ? (★☆☆)
`hint: np.uniform, np.copysign, np.ceil, np.abs, np.where`
#### 30. How to find common values between two arrays? (★☆☆)
`hint: np.intersect1d`
#### 31. How to ignore all numpy warnings (not recommended)? (★☆☆)
`hint: np.seterr, np.errstate`
#### 32. Is the following expressions true? (★☆☆)
```python
np.sqrt(-1) == np.emath.sqrt(-1)
```
`hint: imaginary number`
#### 33. How to get the dates of yesterday, today and tomorrow? (★☆☆)
`hint: np.datetime64, np.timedelta64`
#### 34. How to get all the dates corresponding to the month of July 2016? (★★☆)
`hint: np.arange(dtype=datetime64['D'])`
#### 35. How to compute ((A+B)*(-A/2)) in place (without copy)? (★★☆)
`hint: np.add(out=), np.negative(out=), np.multiply(out=), np.divide(out=)`
#### 36. Extract the integer part of a random array of positive numbers using 4 different methods (★★☆)
`hint: %, np.floor, astype, np.trunc`
#### 37. Create a 5x5 matrix with row values ranging from 0 to 4 (★★☆)
`hint: np.arange`
#### 38. Consider a generator function that generates 10 integers and use it to build an array (★☆☆)
`hint: np.fromiter`
#### 39. Create a vector of size 10 with values ranging from 0 to 1, both excluded (★★☆)
`hint: np.linspace`
#### 40. Create a random vector of size 10 and sort it (★★☆)
`hint: sort`
#### 41. How to sum a small array faster than np.sum? (★★☆)
`hint: np.add.reduce`
#### 42. Consider two random array A and B, check if they are equal (★★☆)
`hint: np.allclose, np.array_equal`
#### 43. Make an array immutable (read-only) (★★☆)
`hint: flags.writeable`
#### 44. Consider a random 10x2 matrix representing cartesian coordinates, convert them to polar coordinates (★★☆)
`hint: np.sqrt, np.arctan2`
#### 45. Create random vector of size 10 and replace the maximum value by 0 (★★☆)
`hint: argmax`
#### 46. Create a structured array with `x` and `y` coordinates covering the [0,1]x[0,1] area (★★☆)
`hint: np.meshgrid`
#### 47. Given two arrays, X and Y, construct the Cauchy matrix C (Cij =1/(xi - yj)) (★★☆)
`hint: np.subtract.outer`
#### 48. Print the minimum and maximum representable value for each numpy scalar type (★★☆)
`hint: np.iinfo, np.finfo, eps`
#### 49. How to print all the values of an array? (★★☆)
`hint: np.set_printoptions`
#### 50. How to find the closest value (to a given scalar) in a vector? (★★☆)
`hint: argmin`