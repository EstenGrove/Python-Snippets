# Data Processing & Parsing
Notes for working with different data type and file types.


## Data Info

- ASCII can only store 128 characters
- Unicode can store over 1,000,000 characters


## Working with Files

##### Opening & Closing Files

__Opening a File__
```python
file = open('someFile.txt')
```

__Closing a File__
- It's important to close a file after working with it to *prevent* resource/memory leaks

###### Close a File: Method 1
```python
reader = open('dog_breeds.txt')
try:
    # Further file processing goes here
finally:
    reader.close()
```
###### Close a File: Method 2
```
with open('dog_breeds.txt') as reader:
    # Further file processing goes here
```
