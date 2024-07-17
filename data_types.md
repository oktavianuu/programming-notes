# Data Types

## Literal

A literal is data whose values are determined by the literal itself . Examples include numbers like `42`, `3.14`, strings like `"Hello"`, and boolean values like `True` and `False`

### Integers

#### octal

If an integer number is preceded by an `0O` or `0o` prefix (zero-o), it will be treated as an octal value. This means that the number must contain digits taken from the [0..7] range only. For example, ```0o72``` or ```0O72``` represents ```58``` in python.
#### hexadecimal
If octal number preceded by ```0o``` or ```0O```, hexadecimal number preceded by ```0x``` or ```0X```. For example, in hexadecimal number, ```0x72``` represents ```114```. 
### Floats
Floats are numbers that have a decimal point. They can represent fractional values and are used when more precision is needed than what integers provide. 
### Strings
Strings are used when you need to process text (like names of all kinds, addresses, novels, etc.), not numbers.
### Boolean Values
They're not as obvious as any of the previous ones, as they're used to represent a very abstract value - **truthfulness**.
Boolean values in python are:
```python
True
False
```
## Key Takeaways
1. Literals are notations for representing some fixed values in code. Python has various types of literals - for example, a literal can be a number (numeric literals, e.g., 123), or a string (string literals, e.g., "I am a literal.").

2. The binary system is a system of numbers that employs 2 as the base. Therefore, a binary number is made up of 0s and 1s only, e.g., 1010 is 10 in decimal.
 Octal and hexadecimal numeration systems, similarly, employ 8 and 16 as their bases respectively. The hexadecimal system uses the decimal numbers and six extra letters.
3. Integers (or simply ints) are one of the numerical types supported by Python. They are numbers written without a fractional component, e.g., 256, or -1 (negative integers).

4. Floating-point numbers (or simply floats) are another one of the numerical types supported by Python. They are numbers that contain (or are able to contain) a fractional component, e.g., 1.27.

5. To encode an apostrophe or a quote inside a string you can either use the escape character, e.g., 'I\'m happy.', or open and close the string using an opposite set of symbols to the ones you wish to encode, e.g., "I'm happy." to encode an apostrophe, and 'He said "Python", not "typhoon"' to encode a (double) quote.

6. Boolean values are the two constant objects True and False used to represent truth values (in numeric contexts 1 is True, while 0 is False.