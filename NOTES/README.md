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
