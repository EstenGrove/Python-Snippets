# Working with String

## String "Special" Operators
Special operators allow you to manipulate strings in specific ways.
- Example Below: ```a``` equals "Hello" and ```b``` equals "World"

|  Operator 	   |       Description 	          |     Example 	                                 |
|----------------|:-----------------------------|:-----------------------------------------------|
|  + 	           |   Concat a string	          |  print(a + b) ='HelloWorld' 	                 |
|  * 	           |   Repeat a string	          |  print(a * a) = 'HelloHello'                   |
| []  	         |   Slice a string	            |  print(a[2]) =  'l'	                           |
| [:]  	         |   Range slice	              |  print(a[2:5]) = 'llo'	                       |
| in  	         |   Membership operator	      |  print("H" in a) = True 	                     |
| not in  	     |   Negative Membership	      |  print("H" not in a) = False	                 |
| %  	           |   Formatting w/ variables(1)	|  print('%d there', a)	= 'Hello there'          |
| {} format  	   |   Formatting w/ variables(2)	|  print('{} there'.format(a))	= 'Hello there'  |
