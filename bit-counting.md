title: Counting Set Bits
date: 2016
tags: Python

###Description:

Write a function that takes an (unsigned) integer as input, 
and returns the number of bits that are equal to one in the binary representation of that number.

countBits(n) should return 5 since 1235 = 10011010010
and there are 5 '1's (set bits) in 10011010010

###Solution:

```python
def countBits(n):
    return bin(n).count("1")
```

### Source:
[CodeWars](https://www.codewars.com/kata/bit-counting/python "CodeWars")
