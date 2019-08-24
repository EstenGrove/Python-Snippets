# Built-In Functions & Commands

### ```dir()```
- will print a sorted list of names that are contained in a specific module

###### Example Usage
```python
import math

content = dir(math)
print(content)
```

### ```importlib``` and ```import_module```
- ```import_module``` is a method used to emulate/mimic import statements and can import any scripts or statements.
- However, since it's NOT a true import you can't continue using is like an import, you need to reload it.
```python
import importlib
importlib.import_module('hello')

# EXAMPLE USAGE

import hello # 1st "import" usage

import hello # 2nd usage
import importlib
import importlib.reload(hello) 
```

----------

### ```globals()``` and ```locals()```
The *__globals__* and *__locals__* built-in functions are used for listing out or returning the names in the **global** and **local** namespace(s).
- The "return type" of both "globals" and "locals" functions is called a "dictionary".
