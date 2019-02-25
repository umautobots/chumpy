chumpy
======

Chumpy is a Python-based framework designed to handle the **auto-differentiation** problem,
which is to evaluate an expression and its derivatives with respect to its inputs, by use of the chain rule.

Chumpy is intended to make construction and local
minimization of objectives easier.

Specifically, it provides:

- Easy problem construction by using Numpy’s application interface
- Easy access to derivatives via auto differentiation
- Easy local optimization methods (12 of them: most of which use the derivatives)

Chumpy comes with its own demos, which can be seen by typing the following:

```python
import chumpy
chumpy.demo() # prints out a list of possible demos
```

Licensing is specified in the attached LICENSE.txt.

## Note:
The chumpy framework was originally by Matthew Loper at https://github.com/mattloper/chumpy. C. Barto (@barcharcraz) modified and updated in this version for pip 10 and Python 3. 
To install, run 
```
python3 -m pip install --user git+https://github.com/umautobots/chumpy.git
```
Tested with pip 10.0.1 and Python 3.6.7. 

Latest revision: July 2018.

