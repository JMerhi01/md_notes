# Libraries and modules

### What are libraries?

A collection of modules and packages that you can use to code more efficiently.

### What are modules?

A set of code/functions with the .py extension that you can call and use in a separate .py file.

##### Differences of Modules and Libraries:

![libraries vs modules.jpg](libraries%20vs%20modules.jpg)

### Examples and Uses

#### **Random**
The random module can be used to generate random numbers. Here are some ways to import and use it:
~~~
import random

print(random.random())

from random import random

print(random())

from random import *

print(random())
~~~
The random module provides functionality for generating random numbers. In the examples provided, we import the random module and then use various functions to generate random numbers. The random() function generates a random float between 0 and 1, while randint() generates a random integer within a specified range.
#### **Math**
The math module provides various mathematical functions. Here's an example of how to use it:
~~~
import math
num_float = 23.66

print(math.ceil(num_float))
~~~
The math module provides a range of mathematical functions. In the example provided, we use the ceil() function to round up a floating-point number to the nearest integer.




