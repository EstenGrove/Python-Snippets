# Python Notes

### String Formatting
```pythong
%s - String (or any object with a string representation, like numbers)

%d - Integers

%f - Floating point numbers

%.<number of digits>f - Floating point numbers with a fixed amount of digits to the right of the dot.

%x/%X - Integers in hex representation (lowercase/uppercase)
```

##### Using Multiple Variables in a String
```python
# Old Method

name = "John"
age = 30  

  print("Hello %s. You are %s years old." % (name, age))
  
# New Method

name = "John"
age = 30 
  
  print("Hello {}. You are {} years old.".format(name, age))
```

### Loops

```python
# "range" Loops  - Syntax: range(start, end, step)

for x in range(10):
  print(x)  
  
  # 0 1 2 3 4 5 6 7 8 9
  
  
  
# "for...in" Loops

names = ["John", "Suzie", "Rachel"]

for name in names:
  print(name)  
  
  # John Suzie Rachel
  
  
# "while" Loops

set = [1, 2, 3, 4, 5, 6, 7]
i = 0
while i < len(set):
  print(set[i])
  i += 1  
  
  # 1 2 3 4 5 6 7
  
  
# "while" w/ "break" Loops

count = 0

while True:
  print(count)
  count += 1
  if count >= 10:
    break
    
    # 0 1 2 3 4 5 6 7 8 9


```
