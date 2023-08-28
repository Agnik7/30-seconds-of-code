---
title: Bitwise Check for Even
type: snippet
language: python
tags: [math]
cover: interior-3
dateModified: 2023‐08‐28T12:35:55+00:00
---

Checks if the given number is even using bitwise operation.

- Check whether a number is odd or even using the bitwise and (`&`) operator.
- Return `True` if the number is even, `False` if the number is odd.
- Comparatively faster than traditional methods, as it checks odd or even in the low-level, i.e., binary form, thus increasing efficiency.

```py
def is_even_bitwise(n):
'''
Checks whether a number is even or odd using bitwise operator.
args: integer
returns: Boolean (True or False), depending on whether the number is even or not.
'''
  return n&1 == 0
```

```py
is_even_bitwise(3) # False
is_even_bitwise(2) # True
```
