# Python Utility Functions

## Description
This project contains several utility functions written in Python to demonstrate various programming concepts, including checking for palindromes using a stack, list comprehensions, bigrams generation, and finding the closest key in a dictionary.

## Usage

### 1. Check if a String is a Palindrome
Use the `is_palindrome` function to check if a given string is a palindrome using a stack.

**Example:**
```python
from palindrome import is_palindrome

print(is_palindrome("radar"))  # Output: True
print(is_palindrome("hello"))  # Output: False

**Functions**

**is_palindrome(input_string)**
Description: Checks if the given string is a palindrome using a stack.
Parameters: input_string (str): The string to be checked.
Returns: bool: True if the string is a palindrome, False otherwise.
**get_bigrams(input_string)**
Description: Generates a list of bigrams from the input string.
Parameters: input_string (str): The string from which to generate bigrams.
Returns: list: A list of bigrams.
**closest_key(input_dict, value)**
Description: Finds the key in the dictionary whose associated list contains a value closest to the beginning.
Parameters:
input_dict (dict): The dictionary with keys and associated lists.
value (str): The value to find in the lists.
Returns: str or None: The key containing the closest match or None if no match is found.
