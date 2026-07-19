# PYSCENE25

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-07-19T08:43:34.492Z  

```py
# Solution as follows

n = int(input())

i = 1
factorial = 1

while i <= n:
    # We need to multiply by i in each iteration
    factorial = i * factorial
    i = i + 1
    
print("The factorial of the given number is:", factorial)
```

---

[View on CodeChef](https://www.codechef.com/problems/PYSCENE25)