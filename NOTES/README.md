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
list = ["John", "Doe"]
str = "Hello %s %s"
  
  print(str % list)

```
