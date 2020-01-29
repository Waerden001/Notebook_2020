# Notebook 2020

This is an experimental project on programming style mathematical notebook. Main points of experiments are 

1. Files arrangement system.
2. Class, functions, database (constants) hierarchy and connections.
3. Realize well-defined, manageable goals in each chunk of code.
## Examples 
```python
>>> class Hilb():
      def __init__(self, X):
        self.base = X
```
In mathematics, this might means we want to consider the Hilbert schemes of points on X. This programming style thinking force us to define 
the mathematical object more clearly. So we can gather relavant functions (theorems, propositions, lemmas) and constants (import, set ups) in one section (class).

```python
>>> def count_points(self, X):
      pass
```
We might have a concrete method to count points on a Hilbert scheme, then the explantion of this method is like defining a function in python or C++. Once again, this forces us to focus on one realizable problem, clearly state the input and output.

```python
>>> def test():
      pass
```
For a code snippet to work properly, we need to test the functions in concrete cases, it's like showing examples, or doing computations explicity.

```python 
"""Construct a Hilb class to ...
:param: 
:rtype: 
"""
```
Comments in code are like remarks in mathematical writing. 

Surely, at the end of the day, math is still just math, but hopefully, programming style writing and project management helps to 
accumulate daily efforts and provide modularity and design patterns in mathematical research writing.  
