# String Methods
### What is method in Java Script ?
![1](./Images/img-1.jpg)
#### Note: In JavaScript functions themselves are objects, so, in that context, a method is actually an object reference to a function.

# Create JavaScript Strings
#### In JavaScript, strings are created by surrounding them with quotes.  There are three ways you can use quotes.
#### • Single quotes: 'Hello'
#### • Double quotes: "Hello"
#### • Backticks: `Hello`
![2](./Images/img-2.jpg)
#### Single quotes and double quotes are practically the same and you can use either of them.
#### Backticks are generally used when you need to include variables or expressions into a string. This is done by wrapping variables or expressions with ${variable or expression} as shown above

## String Methods
![3](./Images/img-3.jpg)
### JavaScript String Length
#### The length property returns the length of a string:
![4](./Images/img-4.jpg)

# Extracting String Parts
### There are 3 methods for extracting a part of a string:
#### slice(start, end)
#### substring(start, end)
#### substr(start, length)

# JavaScript String slice()
### slice() extracts a part of a string and returns the extracted part in a new string.
### The method takes 2 parameters: start position, and end position (end not included).
#### Example
##### Slice out a portion of a string from position 7 to position 13:
![5](./Images/img-5.jpg)
# Note
### `JavaScript counts positions from zero.`
### ` First position is 0.`
### `Second position is 1`

#### Examples
##### If you omit the second parameter, the method will slice out the rest of the string:
![6](./Images/img-6.jpg)
##### If a parameter is negative, the position is counted from the end of the string:
![7](./Images/img-7.jpg)
##### This example slices out a portion of a string from position -12 to position -6:
![8](./Images/img-8.jpg)

# JavaScript String substring()
## substring() is similar to slice().
### The difference is that start and end values less than 0 are treated as 0 in substring().
#### Example
![9](./Images/img%209.jpg)
### If you omit the second parameter, substring() will slice out the rest of the string

# JavaScript String substr()
## substr() is similar to slice().
## The difference is that the second parameter specifies the length of the extracted part.
#### Example
![10](./Images/img-10.jpg)
##### If the first parameter is negative, the position counts from the end of the string.
![11](./Images/img-11.jpg)
# Replacing String Content
### The replace() method replaces a specified value with another value in a string:
![12](./Images/img-12.jpg)
# Note
### The replace() method does not change the string it is called on.
### The replace() method returns a new string.
### The replace() method replaces only the first match
###  If you want to replace all matches, use a regular expression with the /g flag set. See examples below.
#### By default, the replace() method replaces only the first match:
![13](./Images/img-13.jpg)
## By default, the replace() method is case sensitive. Writing FARIDUN (with upper-case) will not work:
![14](./Images/img-14.jpg)
### To replace case insensitive, use a regular expression with an /i flag (insensitive):
![15](./Images/img-15.jpg)
# Note
### Regular expressions are written without quotes.
#### To replace all matches, use a regular expression with a /g flag (global match):
![16](./Images/img-16.jpg)

# JavaScript String ReplaceAll()
### In 2021, JavaScript introduced the string method replaceAll():
![17](./Images/img-17.jpg)
#### The replaceAll() method allows you to specify a regular expression instead of a string to be replaced. If the parameter is a regular expression, the global flag (g) must be set set, otherwise a TypeError is thrown.
![18](./Images/img-18.jpg)
# Converting to Upper and Lower Case
## A string is converted to upper case with toUpperCase():
## A string is converted to lower case with toLowerCase():

#JavaScript String toUpperCase()
![19](./Images/img-19.jpg)
#JavaScript String toLowerCase()
![20](./Images/img-20.jpg)

# JavaScript String concat()
## concat() joins two or more strings:
![21](./Images/img-21.jpg)
# Note
## All string methods return a new string. They don't modify the original string.

#JavaScript String trim()
## The trim() method removes whitespace from both sides of a string:
![22](./Images/img-22.jpg)

# JavaScript String trimStart()
## ECMAScript 2019 added the String method trimStart() to JavaScript.
## The trimStart() method works like trim(), but removes whitespace only from the start of a string.

#### Example
![23](./Images/img-23.jpg)

# JavaScript String trimEnd()
## ECMAScript 2019 added the String method trimEnd() to JavaScript.
## The trimEnd() method works like trim(), but removes whitespace only from the end of a string.
![24](./Images/img-24.jpg)

# JavaScript String Padding
## ECMAScript 2017 added two String methods: padStart() and padEnd() to support padding at the beginning and at the end of a string.
### JavaScript String padStart()
### The padStart() method pads a string with another string:
![25](./Images/img-25.jpg)

# JavaScript String padEnd()
## The padEnd() method pads a string with another string:
![216](./Images/img-216.jpg)

# JavaScript String charAt()
## The charAt() method returns the character at a specified index (position) in a string:
![27](./Images/img-27.jpg)

# JavaScript String charCodeAt()
## The charCodeAt() method returns the unicode of the character at a specified index in a string: The method returns a UTF-16 code (an integer between 0 and 65535).
![28](./Images/img-28.jpg)

# JavaScript String split()
## A string can be converted to an array with the split() method:
![29](./Images/img-29.jpg)
![30](./Images/img-1100000.jpg)







