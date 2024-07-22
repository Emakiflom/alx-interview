# 0x04. UTF-8 Validation

This repository contains solutions for the UTF-8 validation project. The project involves implementing a method to determine whether a dataset represents a valid UTF-8 encoding using Python.

## Background Context

Understanding the UTF-8 encoding scheme is crucial for handling text data correctly. UTF-8 is a variable-length character encoding used for Unicode, capable of encoding all valid character code points in Unicode. This project focuses on implementing a function to validate UTF-8 encoded data by examining the byte-level representation of the data.

## Resources

- [Python Bitwise Operators](https://realpython.com/python-bitwise-operators/)
- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.joelonsoftware.com/2003/10/08/the-unicode-and-character-set-mystery/)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

## Learning Objectives

Upon completion of this project, you should be able to explain the following concepts without the help of Google:

- How to manipulate bits in Python using bitwise operations
- Understanding the UTF-8 encoding scheme and how characters are encoded
- How to represent and work with data at the byte level
- List manipulation in Python and boolean logic

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should use the PEP 8 style (version 1.7.x)
- All files must be executable
- Documentation is required for all modules, classes, and functions
- All functions and coroutines must be type-annotated

## Implementation

The task is to implement a function that determines if a given dataset represents a valid UTF-8 encoding.

### Prototype

```python
def validUTF8(data: List[int]) -> bool:
    """
    Determines if a given data set represents a valid UTF-8 encoding.

    Parameters:
    - data: List of integers, where each integer represents 1 byte of data

    Returns:
    - True if data is a valid UTF-8 encoding, else False
    """
```
## Author
Aman Hablu

GitHub: Emakiflom/alx-interview
