1. Write a  function with one argument x, which is a string, that returns the string with ‘World’ appended to x. The 
argument x should have a default value of ‘Hello’. 

2. Write a function that will return the sum of the integers from m to n: m + … + n. Your function will accept two 
arguments m and n, but m should be optional with a default value of 1.

3. Write a function that returns a single mxn box as a string. The argument n should be optional with default value equal 
to m, so that the default box is a square.

Note:
```
def box(m, n = m):
```
will NOT work as Python will not allow you to put m as a default value for n, since m is an argument. You will have to 
default n to None, and then use an if statement.
